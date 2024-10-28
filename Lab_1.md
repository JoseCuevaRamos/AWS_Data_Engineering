# Querying Data by Using Athena

## Lab overview and objectives

In this lab, you will assume the role of a member of the data science team. You will build a POC using AWS Glue and Athena to analyze the data that's stored in Amazon S3. You want to experiment with Athena by accessing raw data in an S3 bucket, building an AWS Glue database, and querying this database by using Athena.

You also want to determine if you can scale this solution so that others on the team have access. Mary is part of the IAM group in AWS for the data science team and has similar access to the S3 bucket, AWS Glue database, and Athena. However, you limited her access to prevent unnecessary creation of resources. This follows the principle of least privilege, where an administrator limits access to AWS services and resources based upon what permissions are necessary to perform a specific job or task. In one task, you will use an IAM user to test the ability for a data science team member to run Athena managed queries. The IAM user was created for you, and the user belongs to an IAM group that has a policy attached to define permissions.

You ask Mary if she has a few sample datasets that you can use for your experiments. Mary provides access to a dataset that contains taxi trip data for 2017. You will use the data for your POC.

Through some discovery, you learn that Amazon Athena provides this functionality. You explore Athena and its capabilities to see if you can address Mary's needs. Athena is an interactive query service that you can use to query data that is stored in Amazon S3. Athena stores data about the data sources that you query. You can store your queries for reuse, and you can share them with other users.

In this lab, you will learn how to use Athena and AWS Glue to query data that is stored in Amazon S3.

After completing this lab, you should be able to do the following:

- Use the Athena query editor to create an AWS Glue database and table.
- Define the schema for the AWS Glue database and associated tables by using the Athena bulk add columns feature.
- Configure Athena to use a dataset that is located in Amazon S3.
- Optimize Athena queries against a sample dataset. 
- Create views in Athena to simplify data analysis for other users.
- Create Athena named queries by using AWS CloudFormation.
- Review an AWS Identity and Access Management (IAM) policy that can be assigned to users who intend to use Athena named queries.
- Confirm that a user can access an Athena named query by using the AWS Command Line Interface (AWS CLI) in the AWS Cloud9 terminal.
![image](https://github.com/user-attachments/assets/57982a17-fb23-4852-8654-e8c946e03720)

<hr>

