# LUITProject7
Contains the json data file for DynamoDB and the .csv file for s3.
The CF template creates a DynamoDB table that then pulls its data from the s3 bucket.
Afterwards, an ec2 instance is created with a security group that allows SSH access and it also attaches an existing IAM role that was created for this project (DynamoDBReadOnly)
The s3 bucket was created manually
