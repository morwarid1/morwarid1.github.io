---
layout: post
title: Instacart Grocery Basket Exploratory Analysis
#excerpt: "What is a static website generator, and why should I care?"
modified: 2/27/2021, 12:10:34
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

![Pies](https://morwarid1.github.io/images/instacart_images/bk.png) 



- Click [here](https://public.tableau.com/profile/morwarid.najafizada#!/vizhome/InstacartGroceryBasketAnalysis/Dashboard1) to view the full Tableau Dashboard 
- Click [here](https://github.com/morwarid1/Instacart-Grocery-Basket-Analysis-Master) to view my Jupyter Notebook on GitHub and more


--------
### Context 

Instacart is an online grocery store that operates through an app. They want to uncover more information about their sales patterns. My rule as a data analyst is to perform an initial data exploratory analysis of some of their data to derive insights and suggest strategies for better segmentation based on the provided criteria. The Instacart stakeholders are most interested in the variety of customers and their purchasing behaviors in their database. 

-----------
### Objectives

My goal as a data analyst is to create a targeted marketing strategy by answering the questions of sales and Marketing team.


Key Questions from Sales and Marketing team |
---------------------------------------------------|
What are the busiest days of the week and hours of the day are? |
Times of the day when people spend the most money. |
Which departments have the highest frequency of product orders? |
What are the different types of customers in the system and how their ordering behaviors differ? |
What's the distribution among users in regards to their brand loyalty? |
Are there differences in ordering habits based on a customer's loyalty status? |
Is there a difference in ordering habits based on a customer's region? |
Is there a connection between age and family status in terms of ordering habits? |
What different classifications does the demographic information suggest? |
What difference can you find in the ordering habits of different customer profiles? |

-----------
### Process 

Data preparation | Analyzing data |  Visualization of the data |
------------ | ------------- | ------------- |
Cleaned the orders.csv, products.csv,customers.csv, and department.csv datasets | Conducted descriptive analysis | Line Chart, Bar Chart |
Subsetting, consistency checks, combining and exporting data, deriving new variables | Cluster Analysis | Clustering, scatterplot |

### Data Cleaning Process shown in order
-----
![Pies](https://morwarid1.github.io/images/instacart_images/population_flow.png) 


Customer Habits |  |
------------ | ------------ |
3:00 pm to 5:00 pm  |  busiest hours of the day | 
Saturday, Sunday, Friday | busiest days of the week |
Produce and dairy eggs | Popular Departments |
Regular Customers | Customers with highest ordering habits | 

-----------
### Recomendations

Saturday, Sunday, and Friday are the busiest days of the week. I recommend having more products available for a large number of purchases. On the other hand, I recommend doing more marketing on the days with the fewest orders. This way the company can attract new customers. 
![Pies](https://morwarid1.github.io/images/instacart_images/C_order_hour_bar.png) 
![Pies](https://morwarid1.github.io/images/instacart_images/symbols.png) 


Between 3:00 pm to 5:00 pm are the busiest hours of the day. I recommend the marketing team should target to have more customers at morning hours. 
![Pies](https://morwarid1.github.io/images/instacart_images/avgspent_loyalcust.png) 


The produce and dairy eggs department has the highest number of orders. I recommend promoting the departments that are less popular in the marketing ads such as bulk, pets, international, and babies department. 
![Pies](https://morwarid1.github.io/images/instacart_images/depart_ord.png) 


Ordering behaviors of customers differ based on the number of products they order.
We have 3 types of customers. I recommend the marketing team to give extra promotions and discounts to the new Customers. This can encourage them to order more often. 
![Pies](https://morwarid1.github.io/images/instacart_images/loyaly_flag.png) 

![Pies](https://morwarid1.github.io/images/instacart_images/C_Customers.png) 



-------------

Challenges | Solutions
------------ | -------------
I had a hard time creating a new variable | I used loc and aggregation






