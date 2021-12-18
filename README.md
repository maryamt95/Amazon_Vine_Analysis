# Amazon_Vine_Analysis


## Overview of the analysis

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
I focused on the US reviews for video games.

## Results 
* Vine rviews

![image](https://github.com/maryamt95/Amazon_Vine_Analysis/blob/main/vine1.JPG)

* Non-Vine reviews 

![image](https://github.com/maryamt95/Amazon_Vine_Analysis/blob/main/vine2.JPG)

## Summary 

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.Additionally it is possible to analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
