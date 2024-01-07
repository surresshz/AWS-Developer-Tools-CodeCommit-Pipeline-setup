# AWS CI/CD Pipeline
Musician-App NodeJS / React sample application for AWS CI/CD pipeline 

**Amazon Elastic Beanstalk** is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.

**AWS Elastic Beanstalk** is an orchestration service offered by Amazon Web Services for deploying applications which orchestrates various AWS services, including EC2, S3, Simple Notification Service (SNS), CloudWatch, autoscaling, and Elastic Load Balancers.

#### **Steps to setup the CI/CD Pipeline**

- First create a github repo.
- Create application in elastic stalkbean.
- Create environment in the application for your application type ( python , nodejs(in this case) , ruby , etc ).
- You can get demo application domain in the environment.
- Codepipeline create a pipeline there connect your github account there and checkout the settings and give access accordingly.
- **Build** we take the provided code and build it for testing purposes. The code is built in a development environment to allow testing and bug fixes.
- IAM instance profile is IAM-Roles you can create that from IAM
- Once everything is done go back to envir for the domain URL and check if the web application of your github is working and fine
- If you make any changes in your code and push it, it will automatically go to source and deploy it and reflect the changes in the production
