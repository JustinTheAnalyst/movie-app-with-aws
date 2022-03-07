--STILL UNDER DEVELOPMENT--

#1 Building an elegant React Cinema app with continuous integration/delivery (CI/CD) and automatic deployment

#2 Technologies that might be using in this project involve:

- React
- Redux
- AWS S3 and CloudFront
- Terraform
- Slack
- Docker
- Github
- CircleCI for CI/CD
- Heroku

## Set up environment ##

1. Github - create repository; setup multiple online environment (Dev and Staging and Production)
2. CircleCI - setup CI/CD pipeline
3. AWS - using S3 and cloudfront for Storing and Distributing React Cinema App
--> IAM user-ok
--> Buckets-ok
--> CloudFront-ok
4. Setup config.yml
--> Add Build Job to CircleCI Config
--> Add install Command to Build Job
--> AWS S3 CircleCI Job
--> AWS Cloudfront CircleCI Job
--> Create CircleCI S3 Workflow
