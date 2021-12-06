# Amazon_Vine_Analysis
## Overview of the analysis
  The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program, a service that allows manufacturers and publishers to receive reviews of their products and determine if there are any biases between Vine members and Non-Vine member's reviews.

Companies that will pay a fee to Amazon and may provide free products to Vine members who are then required to publish a review. In order to determine if there is any bias towards favorable reviews from Vine members vs. non-members, we need to identify the percentage of 5 star ratings to total rating. As part of this exercise, we were asked to choose from 50 datasets to extract, transform and load into a dataframe in order to complete our analysis. Throughout this analysis, we use:

 - PySpark to extract the dataset, transform the data, connect to AWS RDS instance and load the transformed data into pgAdmin.
 - Google Colaboratory to import PySpark libraries and connect to Postgres in order to create SQL tables and export the results.

## Results
From our analysis, the following results were found: 
### Total Vine 
![](https://github.com/Mousse10/Amazon_Vine_Analysis/blob/main/Resources/Vine%201.PNG)
### Total non-Vine reviews
![](https://github.com/Mousse10/Amazon_Vine_Analysis/blob/main/Resources/Vine%202.PNG)
### Total Vine reviews that were 5 stars
![](https://github.com/Mousse10/Amazon_Vine_Analysis/blob/main/Resources/Vine%203.PNG)
### Total non-Vine reviews that were 5 stars
![](https://github.com/Mousse10/Amazon_Vine_Analysis/blob/main/Resources/Vine%204.PNG)
### Percentage of Vine reviews that were 5 stars
![](https://github.com/Mousse10/Amazon_Vine_Analysis/blob/main/Resources/Vine%206.PNG)
### Percentage of non-Vine reviews that were 5 stars
![](https://github.com/Mousse10/Amazon_Vine_Analysis/blob/main/Resources/Vine%205.PNG)

## Summary
  Based on our results, there seems to be some positivity bias for reviews in the Vine program. The Vine reviews had a higher percentage of 5 star reviews. Further analysis is required in order to make a more accurate assumption. An additional analysis can be done on the remaining ratings for both Vine and Non Vine reviews. The overall percentages for ratings 0 through 5 would be compared and a more accurate conclusion could be made based on the data provided. 
