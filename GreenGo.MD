# 
AWS Amplify
<!-- Build mobile and web apps
Integration with each service of Amazon -->
-> It's make sense tbuild and host Front End Web Application.

Chatbot
<!-- Recognize and receive incoming messages
Process data with built-in inbuilt algorithms
Automated answering system -->
-> You mean AWS Chatbot, I don't think AWS Chatbot is useful, it's just support integration with Slack and Chime. I think chatbot not main feature of us, it take a long time to build and optimize, let consider skip that.

Amazon S3
<!-- Storage
Store garbage’s images, video
Store data of user -->

-> Fine

Amazon DynamoDB
<!-- Database
Cost-effective and scalable
Simple setup anh integration -->
-> Fine

About Architecture of Solution,

Flow AWS Lambda <-> IAM
-> I don't think it's make sense, IAM using to manage user in AWS and permission to access to AWS services. We should to use Cognito to manage user and integration with Lambda to Login. 
For social platform like GreenGo, we can using Cognito to federated login using Facebook account.

Flow Users -> Simple Storage Service -> API Gateway
-> I think it's more clear if we seperate backend and frontend like
Users -> S3
Users -> API Gateway

Overral, it's cost effective solutions, good for operation.

About ideas, 

I already see similar app in market. Let consider reference that and improvement in Vietnam case. We can make it's more friendly with customer and easy access the app.
