# Amazon_Vine_Analysis

## Project Overview
### Main Task:
#### Analyze Amazon reviews written by members of the paid Amazon Vine program
Pick a dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data 
into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll 
write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

#### Dataset I chose:  Amazon Reviews on US Sports
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz

### Deliverables
- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis

### Vine_Review_Analysis
Write a report that summarizes the analysis you performed in Deliverable 2

#### Purpose of Analysis
Using your knowledge of PySpark, Pandas, or SQL, you’ll determine if there is any bias towards reviews that were written as part of the Vine program. For this 
analysis, you'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

#### Results
##### 1.  How many Vine reviews and non-Vine reviews were there?
- Total Vine reviews:  334
- Total Non-Vine Reviews:  61,589

##### 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Total Vine 5 Star Review: 139   
- Total Non-Vine reviews: 32,660 

##### 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine reviews: 41.61%  
- Non-Vine reviews: 53.02% 

#### Summary
Summary of Results pictured below:

<img width="1432" alt="Screenshot 2023-05-30 at 2 38 08 PM" src="https://github.com/mdfjoseph/Amazon_Vine_Analysis/assets/114943747/f79595d5-8099-4017-b096-61118f28fe7c">


