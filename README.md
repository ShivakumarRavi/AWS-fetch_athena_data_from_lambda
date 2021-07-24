# AWS - Get Data from the Amazon Athena table

This project describes, How to fetch the data from the S3 bucket using SQL query.

AWS offers an Amazon Athena service, allowing users to execute the SQL query against the S3 bucket.

Reference: https://medium.com/@shivakumar.mcet/aws-fetch-data-from-amazon-athena-using-api-gateway-and-aws-lambda-4e5729519940

In this article, I described how to create a table in the Amazon Athena and load the data from the S3 bucket (CSV format)

Once the table has been created from the AWS lambda function (Python 3) using the boto3 library, we will send the SQL query to execute in the Amazon Athena and, we will get back the result as lambda response.
