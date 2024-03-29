#  AWS: API, Dynamo and Lambda : 
## AWS API Gateway Overview:

### What is Amazon API Gateway?
Amazon API Gateway is a fully managed service by Amazon Web Services (AWS) that enables developers to create, publish, maintain, monitor, and secure APIs at scale. 
It acts as a gateway between external applications and backend services, facilitating seamless communication and management of API requests and responses.

### Why is Amazon API Gateway an important part of the Serverless ecosystem?
Amazon API Gateway is essential in the Serverless ecosystem as it provides the front-end layer for serverless applications, 
connecting HTTP requests to serverless functions, enabling easy deployment, and scaling without server management concerns.

### How does API Gateway integrate with other AWS services?

Amazon API Gateway integrates with other AWS services by allowing you to directly connect API endpoints to various services, such as AWS Lambda for serverless computing,
AWS S3 for object storage, AWS DynamoDB for NoSQL databases, and more, facilitating seamless data processing and functionality for your applications.

## AWS API Gateway:

### What are the some benefits of using Amazon API Gateway?
Some benefits of using Amazon API Gateway include easy creation and management of APIs at scale,
seamless integration with AWS services, and built-in security features to control access and protect backends from potential threats.

### What two API types might you choose from?

- Two API types you might choose from are RESTful APIs, which use HTTP methods for communication.
- WebSocket APIs, which enable real-time bidirectional communication between clients and servers over a WebSocket connection.
  
## AWS DynamoDB Guide:

### What is DynamoDB?
DynamoDB is a fully managed NoSQL database service provided by Amazon Web Services (AWS).
It offers seamless scalability, low-latency performance, and automatic data replication across multiple regions, making it suitable for various web and mobile applications.

### Under what circumstances would you recommend DynamoDB over MongoDB?
I would recommend DynamoDB over MongoDB when you need a fully managed and serverless NoSQL database with automatic scalability and high availability, 
particularly if you are already using other AWS services, or when you prefer a pay-as-you-go pricing model and don't want to manage database infrastructure.

## Dynamoose:

### What is Dynamoose?
Dynamoose is an npm package and an Object Data Modeling (ODM) library for Node.js that simplifies interaction with Amazon DynamoDB.
It provides a convenient way to model and interact with DynamoDB tables using familiar JavaScript syntax similar to other popular ODM libraries like Mongoose for MongoDB.

### What are some key features of Dynamoose?
- Object Data Modeling (ODM): Dynamoose allows you to define schemas and models for your data, providing a structured and easy-to-use interface for interacting with DynamoDB tables.
- Middleware Support: Dynamoose supports middleware functions, allowing you to add custom logic and behavior during various lifecycle events, such as before/after save, delete, and query operations.
