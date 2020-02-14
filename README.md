# Website Pipeline

This project is a CloudFormation source based on <https://github.com/donhenton/aws-codebuild-samples/tree/master/cloudformation>. It will create a pipeline that moves contents from a specified github account to a website enabled
s3 bucket  via a webhook, so that changes are pushed on commit.

## Running the System

the s3 bucket website needs to be setup first, and is done so using the CF template in other/s3-website.yaml. 
This needs to be done manually, and must be done first.



