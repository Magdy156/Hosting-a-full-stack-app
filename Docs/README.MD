## Continuous Integration

### GitHub

The developer push his code to the GitHub repository which is connected to the CircleCI. GitHub triggers CircleCI when code is pushed to the repository.

### CircleCI

CircleCI reads the .circleci/config.yml file which tells the AWS service what must be done.

Front-end: Runs the build script given in the package.json file. Then uses AWS CLI to upload assets to S3.
back-end: Runs the build script, exports all environment variables from CircleCI configuration. Then uses AWS CLI to upload archive to EBS.

### Elastic Beanstalk

EB URL: http://udagram-api-dev.eba-nxum5usn.us-east-1.elasticbeanstalk.com/

### S3 Bucket

Bucket URL: http://magdsbucket.s3-website-us-east-1.amazonaws.com/
