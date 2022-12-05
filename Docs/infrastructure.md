## AWS

### S3 Bucket

The frontend application is deployed using AWS S3 Bucket. it hosts the static website

Bucket URL: http://magdsbucket.s3-website-us-east-1.amazonaws.com/

### Elastic Beanstalk

The backend server is deployed on AWS Elastic Beanstalk service.S3 bucket extracts and runs the application on an endpoint from that provided by EBS.

EB URL: http://udagram-api-dev.eba-nxum5usn.us-east-1.elasticbeanstalk.com/

### RDS Postgres

The backend server that is deployed on EBS uses AWS RDS service Postgres as a database for storing and retrieving information.

Database URI: postgres://postgres:postgres@database-1.cxp0lojwejyl.us-east-1.rds.amazonaws.com:5432/postgres
