# Amazon_Vine_Analysis
## Overview:
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

### Resources: 
  - Pyspark, PostgresSQL, PgAdmin, AWS, Google Colaboratory 
  - SQL table schema file and Amazon ETL starter code supplied
  
### Objective:
#### Deliverable 1: Perform ETL on Amazon Product Reviews
#### Deliverable 2: Determine Bias of Vine Reviews



### Results:

  -  How many total Vine reviews and non-Vine reviews were there?
      - As you can see from the image below there are a total of 44,714 reviews.
    
   ![image](https://github.com/antxamp/Amazon_Vine_Analysis/blob/main/Resources/Q1_Vine_Review.PNG)
    
  -  How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
      - According to the data that was processed there were a total of 19,663 reviews.  Out of all the verified purchases 10,458 were 5-star vine reviews and 9,205 non-vine reviews.
    
   ![image](https://github.com/antxamp/Amazon_Vine_Analysis/blob/main/Resources/Q2_5Star.PNG)
    
  -  What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
      - I've highlighted 46% of the vine reviews were 5-star
      - While 41% 5-star were non-vine reviews
    
   ![image](https://github.com/antxamp/Amazon_Vine_Analysis/blob/main/Resources/Q3_5Star_Percentage.PNG)
 
### Summary:
Based on the data summary, there isn't sufficient evidence of there being any positivity bias for reviews in the Vine program. Since there is roughly the same percentage of 5 star rated reviews for vine and non-vine reviews, either show a disproportionate percentage from the other.

#### Additional analysis:
You can also use statistical analysis to find further differences on customer votes. In which, more data can change the ratio such as "helpful_votes'” can be reviewed as well as using "verified_purchase" as a threshold. 


 
 
