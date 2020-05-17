ML-Cloud-ETL-Project

Overview

Pulled credit card payment data(csv) from UCI ML repository.
Cleaned data in Transformation.ipynb before storing it in AWS S3 bucket.
Used Spark Python library to pull data from AWS and created ML models in Google Colab.
The notebooks are titled based upon the model employed to train. 
Data was later transformed and loaded into an AWS postgreSQL database in the Transformation notebook.

What still needs to be done: 
Data is very unbalanced, as there is a 3:1 ratio of values for the test. This needs to be corrected, perhaps through random oversampling of the minority.