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
3. **Create a cloudfront distrubution**:CloudFront and S3 can handle any amount of traffic. It’s also cost-effective, as you only pay for what you use
4. **Amazon Route 53:** A highly available Domain Name System (DNS) web service. It is used to route end users’ requests to the CloudFront distribution
5. . **Create a Lambda function**: Create a new Lambda function. This will serve as your backend.
6. . . **Configure DynamoDB**: Create a new table in DynamoDB. This will be used to store your application data.


Open your web application URL in a web browser to use the application.

