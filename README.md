# ADS508_poject
## Goal:
The goal of this project is to detect fraudulent credit card transactions. Fraud transactions will be labeled as 1's and non-fraudulent transactions as 0's, using various predictors and machine learning models such as time card, amount, location, and classification algorithms.
## Data Set
![Credit Card Transactions](https://www.kaggle.com/ealtman2019/credit-card-transactions)
## Report
![Explainability Report](https://github.com/kjcambri/ADS508_poject/blob/main/report.ipynb)
## Overview of Final Project Directory
### - Python Scripts
SageMakerAutopilotDataExplorationNotebook_1.py contains insights about the dataset provided as input to the AutoML job.
create_athena_database.ipynb retrieving stored public s3 bucket and importing pyathena to create database to create Athena Database.
create_athena_tables.ipynb retrieving stores database and setting S3 staging directory. Also, SQL statement to create table 1 and table 2.
data exploration preparation.ipynb getting number of cards not on the dark web and creating dataframe with card information. Also join the three dataframes using pandas.
### - Final output 
![SageMaker Model Quality Report](https://github.com/kjcambri/ADS508_poject/blob/main/report.pdf)
## Future Deployment and Monitoring
Our team will collaborate with the product team to see how A/B tests should be based on a hypothesis that needs to be tested. After setting up the hypothesis, we will perform A/B testing to show the variated version of the product to the experimental group and the existing version of the product to the control group. Our team will monitor the difference in product performance in the experimental group versus the control group to find how effective the new version of the product is. Our goal is to monitor the metric during the test period and find out whether differences existed in the product's performance. 
