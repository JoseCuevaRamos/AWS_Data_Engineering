# Performing ETL on a Dataset by Using AWS Glue

## Lab Overview and Objectives
Big data problems often involve a large number of heterogeneous data sources. As a data analyst, you might not know the schema for some data sources. This is the **variety** aspect of the five Vs of big data: volume, variety, velocity, veracity, and value. In this lab, you will work with **AWS Glue** to perform extract, transform, and load (ETL) for a dataset. AWS Glue can infer a schema from the data types it discovers and builds a **Data Catalog** that contains metadata about the various data sources.

AWS Glue is similar to **Amazon Athena** in that the actual data you analyze remains in the data source. The key difference is that AWS Glue allows you to build a **crawler** to discover the schema, extract the data, transform the schema, and load the data into an AWS Glue database. This data can then be analyzed using SQL statements in Athena.

In this lab, you will learn to use AWS Glue to import a dataset from **Amazon Simple Storage Service (Amazon S3)**. You will then extract the data, transform its schema, and load the dataset into an AWS Glue database for later analysis using Athena.

## Objectives
By completing this lab, you will be able to:

- Access AWS Glue in the AWS Management Console and create a crawler.
- Create an AWS Glue database with tables and a schema by using a crawler.
- Query data in the AWS Glue database using Athena.
- Create and deploy an AWS Glue crawler using an AWS CloudFormation template.
- Review an **AWS Identity and Access Management (IAM)** policy for users to run an AWS Glue crawler and query an AWS Glue database in Athena.
- Confirm that a user with the IAM policy can use the **AWS Command Line Interface (AWS CLI)** to access the AWS Glue database created by the crawler.
- Confirm that a user can run the AWS Glue crawler when source data changes.
![image](https://github.com/user-attachments/assets/96514012-9a18-4a1e-b811-523e15bde43c)
![image](https://github.com/user-attachments/assets/9d6ee5e8-8831-468a-925b-bf0c66c645c6)
