# Amazon_Vine_Analysis

## Overview

Our team has been tasked with using Amazon Web Services (AWS), SQL, and PySpark to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. For our assignment we analyzed an Amazon dataset of various shoe reviews.

## Analysis

For this project our team utilized the Amazon dataset on various shoe reviews and performed the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into SQL. Additionally, we used PySpark to summarize our findings in one dataframe to determine if there is any bias toward favorable reviews from Vine members. 

### Results

Our analysis of the shoe data can be summarized in the below image:

![ Fig 1](https://github.com/lmacera/Amazon_Vine_Analysis/blob/main/Fig%201.PNG )

1.	There were 22 Vine Reviews and 26,987non-Vine reviews.
2.	Of the 22 Vine reviews 13 had 5-star ratings. Of the 26,987non-Vine reviews 14,475 had 5-star ratings.
3.	Of the Vine and non-Vine ratings approximately 59% and 54% were 5-star ratings.

## Summary

In summary our analysis showed there was not a bias among vine members and non-members. Though the number of Vine members is significantly smaller than non-Vine members the percentage of 5- star reviews among the two sets are similar (59% and 54% respectively). Thus, Vine members are likely to give a similar review as a non-member. An analysis that would help support our statement would be to compare the percentage of “helpful votes” to “total votes” among the Vine and non-Vine groups. This would help us determine the usefulness/ effectiveness of reviews among Vine and non-Vine members.
