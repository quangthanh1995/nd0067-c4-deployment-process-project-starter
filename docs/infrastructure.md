# Infrastructure Description

## Infrastructure Diagram
![diagram](Infrastructure-diagram.png)

#### RDS
This application use RDS to store the database, using Postgresql version 12.
RDS link: `database-1.cnutrd1kdjx3.us-east-1.rds.amazonaws.com`

#### Elastic Beanstalk
This application use Elastic Beanstalk to deploy the backend API and connect it to RDS to get the data.
Elasticbean Stalk link: `http://udagram-api-dev.us-east-1.elasticbeanstalk.com/`

#### S3 bucket
This application use S3 bucket to host the frontend webapp, it connect to the Elastic Beanstalk endpoint to get backend API and end user can access S3 endpoint to access the application.
S3 bucket link: `http://myawsbucket-thanhnq10.s3-website-us-east-1.amazonaws.com/`
