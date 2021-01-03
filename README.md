# Product Recommendation Engine
* Applied alternating least squares (ALS) algorithm to build a collaborative filtering recommendation system with purchase data for an online kids’ shoes store on Shopee.com
* Sales from July 2020 to November 2020
* Evaluated models with rank ordering error metric (ROEM) and 78% of recommendations clicked 

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, pyspark  

## Data Cleaning
*	Only use completed orders
* Implicit ratings: the number of purchases of each product from an user
* Data preparation for PySpark ALS

## Data Sparsity
* ~97.23%

## Model Building 
* Split the data into train and tests sets with a test size of 20%
* Applied ALS algorithm and chose rank ordering error metric (ROEM) for implicit ratings to tune parameters

## Model performance on test set
*	**ALS** : ROEM = 0.009318

### Resources
https://github.com/jamenlong/ALS_expected_percent_rank_cv/blob/master/ROEM_function.py
