# aws-lambda-function

This code will do the following Data Ingestion steps


- Download the excel file from the link
- Read the specified sheet from the excel
- convert the rows into list of dictionary
- finally it store the data into AWS S3 bucket(JSON format)

This process also bundled as aws lambda function(Python Lambda Deployment)

You can upload the above zip(included in code) file to S3(size >10MB).

By using zip file you can create a Hassle-Free Python Lambda Deployment function.

You can refer this Link [Hassle-Free Python Lambda Deployment](https://joarleymoraes.com/hassle-free-python-lambda-deployment/). for detailed explanation.

For configuring the AWS CLI refer this link [aws-cli](https://github.com/aws/aws-cli)

