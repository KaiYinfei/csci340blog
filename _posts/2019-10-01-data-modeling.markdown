---
layout: post
title: "Data Modeling"
date: 2019-10-01 10:49:37 -0500
categories: jekyll update
author: brandon_casey
---
I'll divide the assumptions I made by each entity. For the customer I assumed we only cared about their name and some unique id to go along with them. For the item we have the opening price, description, end time, and some unique id for the item. The bid needs to have keys from both of the aforementioned tables; it has a price, time placed, bid id, id of customer who bid, and the id of the item bid for. The winner of the bid has a bid id, customer id, item id, and needs to know the earliest time to choose a winner. I had trouble trying to decide how to add the auction into the diagram. The 5% seems like a strange relationship to represent in a table.
![lab5Draw.io](/assets/img/Lab5.png)
![lab5Vertabelo](/assets/Lab5-2019-10-02_22_50.png)
