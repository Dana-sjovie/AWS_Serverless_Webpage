# AWS_Serverless_Webpage

This is a serverless web application built with HTML, CSS, and JavaScript, and hosted on AWS.

## Architecture

This application uses the following AWS services:

- **Amazon S3** to host static web resources including HTML, CSS, JavaScript, and image files.
- AWS CloudFront: CloudFront is used to deliver your content to users. It fetches your files from the S3 bucket and places copies of the files in different edge locations across the world.
- **Amazon Route 53** Route 53 is a scalable and highly available Domain Name System (DNS) web service. It is used to route end users’ requests to the CloudFront distribution1
- **AWS Lambda** to run the backend code in response to events such as user actions.
- **Amazon DynamoDB** for a managed NoSQL database.

## Setup

1. **Create an S3 bucket**: Create a new bucket in S3. This will be used to host your web application.

2. **Upload files**: Upload your HTML, CSS, and JavaScript files to the S3 bucket.
![image](https://github.com/Dana-sjovie/AWS_Serverless_Webpage/assets/85312549/1528eb2d-e916-49f7-9b0f-cdec14238af0)




3. **Create a cloudfront distrubution**:CloudFront and S3 can handle any amount of traffic. It’s also cost-effective, as you only pay for what you use
![image](https://github.com/Dana-sjovie/AWS_Serverless_Webpage/assets/85312549/5b480261-42a9-4e81-92a1-fdf6ac667d8d)



4. **Amazon Route 53:** A highly available Domain Name System (DNS) web service. It is used to route end users’ requests to the CloudFront distribution
![image](https://github.com/Dana-sjovie/AWS_Serverless_Webpage/assets/85312549/1ca8c304-c166-4c5a-8ed3-6bd607025d8d)




5. . **Create a Lambda function**: Create a new Lambda function. This will serve as your backend.
![image](https://github.com/Dana-sjovie/AWS_Serverless_Webpage/assets/85312549/33e551af-00c0-4b17-b45b-79b77d261dd2)




7. . . **Configure DynamoDB**: Create a new table in DynamoDB. This will be used to store your application data.
![image](https://github.com/Dana-sjovie/AWS_Serverless_Webpage/assets/85312549/04deaadc-d8ea-4441-b68c-9f93e7caaeab)




Open your web application URL in a web browser to use the application.

