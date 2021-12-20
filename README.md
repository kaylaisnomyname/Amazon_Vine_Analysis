# Amazon_Vine_Analysis

## Overview
Purpose of this practice is to analyze Amazon reviews for luggages from paid(Vine) and unpaid (non-Vine) customers. This challenge is to practise ETL process using PySpark, Pandas, SQL as well as AWS database. 

Data: Amazon reviews for US Luggages  
Data Source: [source link](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Luggage_v1_00.tsv.gz)
## Results  
Among total 348,657 reviews, there are 7,055 reviews which have more than 20 votes, and 6,711 that have more than 50% helpful votes. The following results are derived from the 6,711 useful records.
- There are total 21 Vine reviews and 6690 non-Vine reviews.
- There are total 3,458 5-stars reviews: 10 of them are from Vine users and 3,448 from non-Vine customers.
- Among all the helpful reviews: 0.15% of them is from Vine users and 51.38% is from non-Vine users.
###### image1  
![image1]()  

## Summary
According to the results, there are 10 out of 21 Vine reviews are 5-stars, or about 48%. There are 3448 out of 6690 non-Vine users rated 5-stars, or 51.5%. In short, about half of the customers, both paid and non-paid, have rated 5 stars on their reviews. Also, among the helpful reviews, 5,240 out of 6711 are from verified purchases, about 78%. Overall, the reviews of luggage sales are considered somewhat fair.  