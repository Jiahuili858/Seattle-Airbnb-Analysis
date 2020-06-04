# Analysis on Seattle Airbnb market

## Table of Contents
1. Libraries
2. Project Motivation
3. File Descriptions
4. Summary of Results
5. Acknowledgements


## Libraries Required
- pandas
- numpy
- seaborn
- pyLDAvis
- pprint
- wordcloud
- langdetect
- gensim
- spacy
- unidecode
- re


## Project Motivation
The goal of this project is to understand the airbnb market in Seattle, which can help the travelers to make better decisions when they book accommodations. Here are the questions I am delving into:
  1. What are the busiest times to visit Seattle? By how much do prices increase?
  2. What are the common type of property in Seattle? How do the prices of common property differ in neighborhoods during peak periods?
  3. On average how many days are the listings available? Is there any trend that exists?
  4. What are the key topics based on the reviews?

 
 ## File Description
The [Data](https://github.com/Jiahuili858/Seattle-Airbnb-Analysis/tree/master/Data) folder contains the dataset. It includes three csv files:
- Listings.csv: including full descriptions and average review score
- Reviews.csv: including unique id for each reviewer and detailed comments 
- Calendar.csv: including listing id and the price and availability for that day


## Summary of Results
- The summer period, from June to August, shows a significant increase in average pricing. Prices in July on average increase   10.25% than the overall average price and the prices in August increases 9.21%. Prices on Friday and Saturday are higher.
- The property types House and Apartment dominate the market in Seattle, which account for 45.4% and 44.7%. Neighborhood has a huge impact on the listings price. For example, We need to spend $405 for a house in an expensive neighborhood, while we can just pay $76 to live a different area. 
- On average, a property is available in the market for 244 days in a year (around 67% of the time). There is an increasing percentage of availability over time. However, it is highly possible the increased average price in summer is due to the relatively limited listings available in the market.
- Reviewers care about four main aspects when they rate: the location, view, confort(feel like home) and interior.


## Acknowledgement
Data are provided by Kaggle: [Boston Airbnb Open Data](https://www.kaggle.com/airbnb/seattle)


