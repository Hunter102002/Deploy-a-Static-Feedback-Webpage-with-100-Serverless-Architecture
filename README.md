# Deploy a Static Feedback Webpage with 100% Serverless Architecture

## Objective

This project aimed to deploy a static feedback webpage using a serverless architecture on AWS. The goal was to collect feedback, store the details in DynamoDB, and images in S3 using AWS Lambda and API Gateway. This project demonstrates intermediate-level skills in AWS resource management, serverless function deployment, and integration of various AWS services.

### Skills Learned

- AWS S3 Management: Creating and configuring S3 buckets for image storage and static website hosting.
- AWS DynamoDB Management: Setting up and managing DynamoDB tables for storing feedback details.
- AWS Lambda Deployment: Developing and deploying Lambda functions for processing feedback.
- API Gateway Configuration: Creating and configuring REST APIs to trigger Lambda functions.
- CORS Configuration: Enabling and managing Cross-Origin Resource Sharing (CORS) for secure web interactions.

### Tools Used

- Amazon S3: For storing webpage content and uploaded images.
- Amazon DynamoDB: For storing feedback details.
- AWS Lambda: For serverless processing of feedback submissions.
- Amazon API Gateway: For creating and managing RESTful APIs.
- AWS Management Console: For configuring and managing all AWS resources.

### Outcome
The project successfully demonstrated the deployment of a static feedback webpage using a serverless architecture. The solution ensures that feedback details and images are securely processed and stored without the need for any server management, adhering to best practices for cloud-native applications.

By completing this project, I have demonstrated the ability to effectively manage and integrate various AWS services, showcasing skills in serverless architecture, resource management, and secure data handling in the cloud.

## Steps

Create a DynamoDB Table

<img width="1470" alt="Screenshot 2024-05-21 at 7 17 20 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/eda41c85-a880-4303-9348-537323538e58">

Creating a image storing S3 bucket and adding bucket policy


<img width="1314" alt="Screenshot 2024-05-21 at 7 19 04 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/e58a36f3-e7fa-4319-b835-907a1516036e">

Create a S3 bucket for our web content

<img width="1310" alt="Screenshot 2024-05-21 at 7 23 01 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/dfe51078-bd8c-41cb-9173-3e4cdb66f83d">

Download and upload premade webpage content


<img width="798" alt="Screenshot 2024-05-21 at 7 25 32 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/4436bb1a-0932-4b12-b096-514e42669785">

Enable proper web hosting settings

<img width="802" alt="Screenshot 2024-05-21 at 7 27 37 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/810df5ac-0a9c-45a1-81b0-008b8c58df64">

Test Public IP

<img width="746" alt="Screenshot 2024-05-21 at 7 29 10 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/951e23ec-5b65-4836-a2e6-ff6f849f18d3">


<img width="749" alt="Screenshot 2024-05-21 at 7 29 21 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/d96f6cfa-3cfc-4e05-83b9-a3235a044782">

Create Lambda function and upload premade code


<img width="1349" alt="Screenshot 2024-05-21 at 7 30 48 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/33a2dfd5-a86d-4739-a1e2-1af1ca5cfe1e">


<img width="1309" alt="Screenshot 2024-05-21 at 7 32 41 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/4d900999-4932-4281-8436-33c457986577">

Create a resource and method for the API

<img width="1128" alt="Screenshot 2024-05-21 at 7 34 04 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/78091e4d-72f2-47a1-a537-982500cc6ab0">

<img width="1075" alt="Screenshot 2024-05-21 at 7 35 19 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/11ea876c-f37b-4831-a903-cf028f9a061c">

Test API

<img width="1071" alt="Screenshot 2024-05-21 at 7 36 25 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/812761d8-aeac-4b04-bd27-a25ab9a373ba">


<img width="743" alt="Screenshot 2024-05-21 at 7 38 35 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/be604023-8640-4ee8-bb2d-ecc9e86f5b41">

Test Website form

<img width="737" alt="Screenshot 2024-05-21 at 7 39 34 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/de6d2300-72d0-4e23-b127-677ae40b6736">

Verify forms have been placed into bucket 

<img width="743" alt="Screenshot 2024-05-21 at 7 40 21 PM" src="https://github.com/Hunter102002/Deploy-a-Static-Feedback-Webpage-with-100-Serverless-Architecture/assets/98543129/0a7dbee5-8e83-4913-8ebd-1fb27199cccf">
