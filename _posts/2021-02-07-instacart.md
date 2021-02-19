---
layout: post
title: Instacart Grocery Basket Exploratory Analysis 
excerpt: "What is a static website generator, and why should I care?"
modified: 2/29/2016, 9:00:24
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---



![Pies](https://morwarid1.github.io/images/instacart_images/bk.png) 



- Add Report file as downloadable ?
- Link to the Tableau ?



### Context 
Instacart is an online grocery store that operates through an app. They want to uncover more information about their sales patterns. My rule as a data analyst is to perform an initial data exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria. The Instacart stakeholders are most interested in the variety of customers and their purchasing behaviors in their database. 


### Objectives
My goal as a data analyst is to create a targeted marketing strategy by answering the questions of sales and Marketing team.


Key Questions from Sales and Marketing team |
---------------------------------------------------|
What is the busiest days of the week and hours of the day are? |
Times of the day when people spend the most money. |
Which departments have the highest frequency of product orders? |
What are the different types of customers in the system and how their ordering behaviors differ? |
What's the distribution among users in regards to their brand loyalty? |
Are there differences in ordering habits based on a customer's loyalty status? |
Is there a difference in ordering habits based on a customer's region? |
Is there a connection between age and family status in terms of ordering habits? |
What different classifications does the demographic information suggest? |
What difference can you find in the ordering habits of different customer profiles? |


### Process 

Data preparation | Analyzing data |  Visualization of the data
------------ | ------------- | -------------
Cleaned the orders.csv, products.csv,customers.csv, and department.csv datasets | Conducted descriptive analysis | Line Chart, Bar Chart
Subsetting, consistency checks, combining and exporting data, deriving new variables | Cluster Analysis | Clustering, scatterplot 

### Data Cleaning Process shown in order
![Pies](https://morwarid1.github.io/images/instacart_images/population_flow.png) 




  
  
### Results
The busiest days of the week are the first and last day of the week. And from 4 to 5 am is the busiest hour of the day. 
![Pies](https://morwarid1.github.io/images/instacart_images/avgspentweek_loyalcust.png) 

![Pies](https://morwarid1.github.io/images/instacart_images/avgspent_loyalcust.png) 



People spend more money in the morning before 10 am. 
![Pies](https://morwarid1.github.io/images/instacart_images/C_order_Hour.png) 

Produce and dairy eggs has the highest number of orders
![Pies](https://morwarid1.github.io/images/instacart_images/depart_ord.png) 

Ordering behaviors of customers differ based on the number of products they order.
We have 3 types of customers: 
![Pies](https://morwarid1.github.io/images/instacart_images/loyaly_flag.png) 
![Pies](https://morwarid1.github.io/images/instacart_images/C_Customers.png) 

Region play role in the ordering habits of customers. 
![Pies](https://morwarid1.github.io/images/instacart_images/C_Region.png) 
![Pies](https://morwarid1.github.io/images/instacart_images/Region_income.png) 







### Recomendations

Challages | Solutions
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

### Tools Used 





### The Python Codes will be added ....?

Want to see something else added? <a href="https://github.com/poole/poole/issues/new">Open an issue.</a>
