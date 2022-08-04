# STORM
AWS Amplify: for front-end of our web and app to visualize data, state of forest and user interface
-> Good choice
Amazon Cognito: to authenticate user, protect service from DDOS attack and cyber criminal
-> Cognito is good, I don't think anti DDOS attack and cyber criminal is an capability of Cognito. We have service WAF & Shield Advanced for that.
AWS Lambda: set up several functions like visual data, retrieve data, upload data,
-> Good, it's total fine for backend side. Simple and easy for operation.
Amazon S3: storage data for machine learning and forecast disaster and weather
-> Good
Dynamo DB: database use for request data from user
-> Good
Amazon API Gateway: for call AWS Lambda functions from web browser
-> Good
Amazon SageMaker: train AI,ML model for forecast disater and weather
-> I don't forecast disaster and weather is very complex. Consider using public API instead of buy your own.
Let concentrate about core feature and make it work first.
IMO: I think the ideas still must be clear what the core and useful to support with forest protector. What data should be collected to Visualize.