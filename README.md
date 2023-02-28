# Amazon_Vine_Analysis

## Analysis Overview
The primary objective of this project was to conduct a comprehensive analysis of Amazon reviews authored by the Amazon Vine program's paying members. Employing PySpark, I performed a systematic ETL process to extract, transform, and establish a connection with an AWS RDS instance to ultimately load the transformed data into pgAdmin. Further utilizing PySpark, I analyzed the dataset pertaining to beauty sales, evaluating the propensity towards favorable reviews from Vine members.

## Resources
* Data source:
  * [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
  * [Amazon Beauty Review Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Beauty_v1_00.tsv.gz)

* Software:
  * Google Colab
  * pgAdmin4
  * AWS

## Outcome

### Number of Vine and non-Vine reviews
![](images/vineandnonvine.png)

### How many 5 star reviews there were from both Vine and non-Vine members
![](images/fivestar.png)

### Percentage of 5 star reviews from both Vine users and non-Vine members
![](images/percentageof5stars.png)

## Summary
The review summary illustrates a greater count of non-Vine reviews as compared to Vine reviews, indicating that positive feedback regarding the beauty products is being generated through both organic and paid channels.
