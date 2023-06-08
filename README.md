# Automating Infrastructure Deployment For The CafeApp 

 I used AWS CloudFormation to deploy a static version of the café website .then deployed the dynamic café website as a web application.
For the dynamic website, I used a CI/CD pipeline that used AWS CodeCommit, AWS CodePipeline, and AWS CloudFormation. 
In addition, duplicated both the network resources and the café application resources to another AWS Region.


# Steps


1- Deployed a virtual private cloud (VPC) networking layer by using an AWS CloudFormation template.

2- Deployed an application layer by using an AWS CloudFormation template.

3- Used Git to invoke AWS CodePipeline, and to create or update stacks from templates that are stored in AWS CodeCommit





