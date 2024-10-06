# Lita_Class_Documentation 

### Project Title: Sales Analysis 

### Project Overview
---
This Data Analysis Project aims to generate insights into the sales performance of various brands across different countries over the past month and years. By analyzing the various parameters in the data received we seek to identify top performing brand and region, uncover insights into sales trends and patterns and tell compelling stories around our data from the insights gotten. 
### Data Sources
---
The Primary Source of the data used is an online source data that can be freely downloaded from an open source online or data repository sites.
### Tools Used
---
- Microsoft excel For Data Cleaning
- SQL - Structured Query Language for Querying of data
- GitHub for Portfolio Building

### Data Cleaning and Preparation 
---
In the initial phase of the data cleaning and preparations, we performed the following actions;
1. Data loading and Inspection
2. Handling missing variables
3. Data cleaning and formatting

### Exploratory Data Analysis 
---
EDA involves the exploring of the data to ask some quetsions such as;
- what is the overall sales trend
- which brand are top sellers
- which country is at the peak of sale

### Data Analysis 💻
---
This is where we include some basic line of code or queries or even some of the DAX expressions used during your Analysis

```SQL
SELECT * FROM InternationalBreweries
```
```SQL
SELECT BRANDS, SUM(PROFIT) as TOTALPROFIT FROM InternationalBreweries WHERE COUNTRIES = 'NIGERIA' GROUP BY BRANDS ORDER BY 2 DESC
```

|Heading 1|Heading 2|Heading 3|
|---------|---------|---------|
|Table 1|Table 2|Table 3|

