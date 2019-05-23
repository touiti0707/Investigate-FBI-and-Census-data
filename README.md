## Date created
Project uploaded on 23/05/2019

# Investigate FBI gun data to understand which variables are most associated with high gun per capita

## Introduction

In this project I investigate the FBI's National Instant Criminal Background Check System (NICS), which is used to determine whether a prospective buyer is eligible to buy firearms or explosives. Gun shops will call into this system to ensure that each customer does not have a criminal record or isn't otherwise ineligible to make a purchase. 

The dataset (*gun_data.xls*) contains the number of firearm checks by month, state and type. It is completed by another dataset (*U.S. Census Data.csv*) which contains several census variables at the state level.

Over the course of the report, I will try to answer three questions:
* **What is the overall trend of gun purchases?**
* **Which states have high gun per capita?**
* **Are low education, low income or high poverty associated with high gun per capita?**

First I am going to wrangle the data and clean it so I can proceed with an exploratory data analysis. During this second step, I will compute useful statistics and create visualizations to get a better understanding of the data. Finally, I will summarize my findings and answer the questions.

### **You can have access to all my detailed code and analysis in the Jupyter Notebook.**

## Software requirements
You should have Python3, Numpy, pandas and Jupyter Notebooks.

## Credits
Thanks to the Udacity team for this great project which is part of the Data Analyst Nanodegree Program!
