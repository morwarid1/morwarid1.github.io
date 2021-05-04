---
layout: post
title: Rockbuster Stealth Data Analysis Project 
excerpt: "Databases & SQL (Extract, transform, load): Rockbuster Stealth LLC is a movie rental company that used to have stores around the
world. Facing stiff competition from streaming services such as Netflix and Amazon Prime,
the Rockbuster Stealth management team is planning to use its existing movie licenses to
launch an online video rental service in order to stay competitive. "
modified: 2/27/2021, 12:10:34
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---


![Pies](https://morwarid1.github.io/images/Rockbuster/RDMS.png) 

- Click [here](https://public.tableau.com/profile/morwarid.najafizada#!/vizhome/RockbusterStealthDataAnalysisProject/Rockbuster) to view the full Tableau Dashboard 
- Click [here](https://github.com/morwarid1/Rockbuster-Stealth-Data-Analysis-Project) to view my SQL codes on GitHub and more

--------------

Sample of my queries done in SQL  | 
------------ | 
Common Table Expression (CTE) |
Joining Tables | 
Subqueries |
### Context 

Rockbuster Stealth LLC is a movie rental company that used to have stores around the
world. Facing stiff competition from streaming services such as Netflix and Amazon Prime,
the Rockbuster Stealth management team is planning to use its existing movie licenses to
launch an online video rental service in order to stay competitive. The main purpose of this sample project is to launch a strategy for the new online video rental service. This project will help to better understand the Rockbuster Database and have better insight for future Rockbuster product investments. My rule as a data analyst is to help with the launch of the strategy by answering any ad-hoc business questions that other department might have. My first task will be loading all of the Rockbuster's data into a relational database management system (RDBMS). Rockbuster data set contains information about Rockbuster's film, inventory, customers, and payments, among other things.


---------------------------------
### Common Table Expression (CTE)
- Finding the average amount paid by the top 5 customers 
![Pies](https://morwarid1.github.io/images/Rockbuster/CTE_1.png) 

- Finding out how many of the top 5 customers are based within each country. 
![Pies](https://morwarid1.github.io/images/Rockbuster/CTE_2.png) 

---------------
### Joining Tables
- Finding Top 10 countries for Rockbuster
![Pies](https://morwarid1.github.io/images/Rockbuster/JT_1.png) 

- Finding Top 10 cities within top countries identified
![Pies](https://morwarid1.github.io/images/Rockbuster/JT_2.png) 

- Finding Top 5 customers in the top cities paid highest total amounts
![Pies](https://morwarid1.github.io/images/Rockbuster/JT_3.png) 

---------------
### Subqueries
- Finding average amount paid by the top 5 customers
![Pies](https://morwarid1.github.io/images/Rockbuster/SQ_1.png) 

- Finding how many of the top 5 customers are based within each country
![Pies](https://morwarid1.github.io/images/Rockbuster/SQ_2.png) 
