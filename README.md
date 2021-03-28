# Amazon_Vine_Analysis

## Overview of the analysis   
For this challenge, we were assigned the task of analyzing Amazon reviews written by members of the paid Amazon Vine program. We were given 50 datasets and I chose to analyze the reivews for baby products. We were then to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and the load the transformed data into pgAdmin. We then used PySpark to determine if there was any bias toward favorable reviews from Vine members in the dataset. </br>

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
1. How many Vine reviews and non-Vine reviews were there?</br>
There was a total 463 paid Vine reviews.</br>
![totalpaid](https://github.com/echuung94/Amazon_Vine_Analysis/blob/main/images/totalpaid.png)</br>
There was a total of 25094 unpaid Vine reviews.</br>
![totalunpaid](https://github.com/echuung94/Amazon_Vine_Analysis/blob/main/images/totalunpaid.png)

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?</br>
There was a total of 202 paid Vine reviews that were 5 stars.</br>
![paid5star](https://github.com/echuung94/Amazon_Vine_Analysis/blob/main/images/paid5star.png)</br>
There was a total of 12033 unpaid Vine reviews that were 5 stars.</br>
![unpaid5star](https://github.com/echuung94/Amazon_Vine_Analysis/blob/main/images/unpaid5star.png)

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?</br>
Approximately 43.62% of Vine reviews were 5 stars.</br>
![paidpercent](https://github.com/echuung94/Amazon_Vine_Analysis/blob/main/images/paidpercent.png)</br>
Approximately 47.95% of non-Vine reviews were 5 stars.</br>
![unpaidpercent](https://github.com/echuung94/Amazon_Vine_Analysis/blob/main/images/unpaidpercent.png)

  ## Summary
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.</br>  
The data results show that there is no posivity bias for reviews in the Vine program. The percent for vine reviews were 43.6% and non-vine reviews were 47.9%, which shows that the percentages are not significantly different from one another. Since there are strong judgments on each baby products used by various people, additional analysis for this could be to retreive age and gender for each of the reviewers to see if they have an affect on the positivity bias for reviews in the Vine program. 
