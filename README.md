# AWS_Serverless_Webpage

This is a serverless web application built with HTML, CSS, and JavaScript, and hosted on AWS.

## Architecture

This application uses the following AWS services:

- **Amazon S3** to host static web resources including HTML, CSS, JavaScript, and image files.
- **AWS Lambda** to run the backend code in response to events such as user actions.
- **Amazon API Gateway** for RESTful API creation and deployment.
- **Amazon DynamoDB** for a managed NoSQL database.

## Setup

1. **Create an S3 bucket**: Create a new bucket in S3. This will be used to host your web application.

2. **Upload files**: Upload your HTML, CSS, and JavaScript files to the S3 bucket.

3. **Create a Lambda function**: Create a new Lambda function. This will serve as your backend.

4. **Set up API Gateway**: Set up a new API in API Gateway. This will be used to trigger your Lambda function.

5. **Configure DynamoDB**: Create a new table in DynamoDB. This will be used to store your application data.

## Deployment

To deploy the application, follow these steps:

1. **Enable static website hosting for your S3 bucket**.

2. **Upload your web application files to the S3 bucket**.

3. **Create a new Lambda function and add your backend code**.

4. **Create a new API in API Gateway and connect it to your Lambda function**.

5. **Create a new DynamoDB table and update your Lambda function to use it**.

6. **Update your web application to call the API Gateway URL**.

## Usage

Open your web application URL in a web browser to use the application.

