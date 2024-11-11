# Storing and Analyzing Data by Using Amazon Redshift

## Lab Overview and Objectives
Mary, a member of the data science team, often works with large datasets and columnar data stores. To support her use cases, you have decided to explore Amazon Redshift for your next proof of concept (POC).

Mary has provided a sample dataset for the POC: a large music ticket sales dataset stored in a public Amazon Simple Storage Service (Amazon S3) bucket. Data analysts frequently work with extensive datasets, such as data warehouses containing multiple petabytes or data lakes that are even larger. Amazon Redshift is optimized for handling large datasets using columnar data storage, which enhances query performance and reduces storage costs.

In this lab, you will implement an Amazon Redshift cluster as part of your analytics pipeline. You will retrieve data from an Amazon S3 dataset, load it into a Redshift database, and query the data for analysis.

## Objectives
By completing this lab, you will be able to:

- Review an AWS Identity and Access Management (IAM) role's permissions to access and configure Amazon Redshift.
- Create and configure a Redshift cluster.
- Create a security group for a Redshift cluster.
- Create a database, schemas, and tables with the Redshift cluster.
- Load data into tables in a Redshift cluster.
- Query data within a Redshift cluster using the Amazon Redshift console.
- Query data within a Redshift cluster using the API and AWS Command Line Interface (AWS CLI) in AWS Cloud9.
- Review an IAM policy with permissions to run queries on a Redshift cluster.
- Confirm that a data science team member can run queries on a Redshift cluster.

![image](https://github.com/user-attachments/assets/21e30ffe-5dec-40ca-82a1-1b3602c8cfd5)
![image](https://github.com/user-attachments/assets/97d4a8a1-8db7-4808-9cca-b30b7fba923b)

