# Extract, transform, and load (ETL) pipeline using AWS services to analyze data from the Spotify API for top songs

This project extracts data from the Spotify API for the top songs, transforms the data using AWS Glue and Lambda functions, and loads the data into S3 buckets. The transformed data is then analyzed using Athena.

## Prerequisites

An AWS account

Spotify developer account and client ID/secret
Python 3.x installed on your local machine
AWS CLI installed on your local machine


## Steps
Clone the repository to your local machine.
Create an S3 bucket to store your raw data.
Create an S3 bucket to store your transformed data.
Create an AWS Glue crawler to create a metadata table for your raw data in the S3 bucket.
Create a Lambda function to transform your raw data and save it to the transformed data S3 bucket.
Schedule your Lambda function to run on a regular basis.
Create an Athena table to analyze your transformed data.
Run queries on your Athena table to analyze your data.
For detailed steps and configuration options, please refer to the project documentation.


(<https://github.com/Zia-Said/Spotify_End_to_End_Data_Engineering_Project/blob/main/Spotify_ETL_Pipeline_in_AWS_Project.png>)
