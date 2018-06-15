# Start Learning Python

## WomenTechWomenYes

This was the first project that I did in Metis. The purpose of the project for me was to learn Pandas and data cleaning.

The scenario is that a hypothetical organization called WomenTechWomenYes wants to promot their annual gala in summer in New York. They have limited human resource for this purpose and want to know how to optimally allocate their people in New York Metro stations. We need to use MTA data to recommend them an optimal allocation.


## Data Cleaning
For data cleaning purpose, we started by cleaning the name of the columns to make sure they are named properly without extra space or charechters. Then we check to see if the numeric data have correct type. After that we looked for outliers to make sure they are not going to affect our results. 

## Finding optimal allocation
We define a score to rank the stations:
Score = (0.55 * Station Rank) +0.15*(Income Rank + Tech Rank+ Starbucks Rank)
We found the top 10 stations with most enteries. That is going to be the Station Rank.
Between these stations, we also ranked them based on being in the zipcodes with most tech companies, being in the zipcode with most median income and having more Starbuck close to the stations. 
The final top 5 stations recommended for sending the street team. 
We also find the best day and hours that they can send their teams to these stations. As you can see in the image below, the best hours are from 12 PM to 4 PM during the weekdays.

![alt_text](https://github.com/mymnazari/mymnazari.github.io/blob/master/images/hours.png)



