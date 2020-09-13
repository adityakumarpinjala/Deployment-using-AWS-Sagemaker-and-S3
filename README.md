# Deployment-using-AWS-Sagemaker-and-S3


Notes:
1.First create one free AWS tier account which is having 12 months of trail period
2.Then Search sagemaker in aws console
3.Then go to create notebook instance.
4.Have Iam role-suppose if we create S3 bucket,then that S3 bucket can be accessed to that specific application.
5.we have any specific S3
6.Use of S3 bucket is for saving the data like model,train,test.
7.import sagemaker,this is for excuting any inbuilt containers like xgboost
8.boto3,we can read the data from s3 bucket from our local public python env 
9.s3_input,Session -we need the session to access S3 bucket
