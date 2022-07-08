# Amazon_Vine_Analysis
Pyspark,AWS and ETL using PgAdmin
# Overview of the analysis of the Vine program:
This project is intended to practise our ETL skills, we are going to use the dataset from Amazon review dataset
(https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Wireless_v1_00.tsv.gz). We will perform our ETL using PySpark, connecting our data storage from amazon AWS to pgAdmin as our database engine. 
## Results:
  - with the unpaid and paid program reviews, the results are shown below
  - ![Total umber of paid reviews by star rating](https://github.com/elzmanzi/Amazon_Vine_Analysis/blob/main/Results/paid_reviews_byStar_ratings.PNG)
  - ![Total umber of unpaid reviews by star rating](https://github.com/elzmanzi/Amazon_Vine_Analysis/blob/main/Results/unpaid_reviews_byStar_ratings.PNG)
  - The total number of paid reviews is 613 and the one for non paid reviews is 64968
  - see below percentages of both paid 5 star reviews with 36.22% and unpaid 5 start reviews with 47.01%
  
    ![percentage of paid reviews](https://github.com/elzmanzi/Amazon_Vine_Analysis/blob/main/Results/percentage_of_paid_5Sreviews.PNG)
    ![percentage of unpaid reviews](https://github.com/elzmanzi/Amazon_Vine_Analysis/blob/main/Results/percentage_of_unpaid_reviews.PNG)

## Summary:
in closing, with the analysis we made, i may suggest to look deeper of how the reviews were before paying for 5 star reviews, what is the difference in percentages. I can coclude by saying that in the data there is positivity bias for reviews in the Vine program.
