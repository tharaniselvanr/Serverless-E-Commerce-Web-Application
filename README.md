# Serverless-E-Commerce-Web-Application
Serverless E-Commerce Web Application using AWS
 
Serverless E-Commerce Web Application Using AWS

Project Overview

This project is a serverless e-commerce web application built using AWS services. It provides a scalable and cost-effective architecture for hosting an online shopping application without managing traditional servers.

AWS Architecture

                         USER
                           ↓
                    Amazon CloudFront
                           ↓
                    Amazon S3
                 (Frontend Website)
                           ↓
                    API Gateway
                           ↓
                       Lambda
                           ↓
                    Amazon DynamoDB
                      (Database)
                           ↓
                    Amazon Cognito
                 (User Authentication)
AWS Services Used

- Amazon S3 – Hosts the frontend website.
- Amazon CloudFront – Delivers website content quickly to users.
- Amazon API Gateway – Handles API requests.
- AWS Lambda – Runs backend logic without managing servers.
- Amazon DynamoDB – Stores e-commerce application data.
- Amazon Cognito – Provides user authentication and login.
 
Project Flow

1. User accesses the e-commerce website through Amazon CloudFront.
2. The frontend website is hosted on Amazon S3.
3. User requests are sent to Amazon API Gateway.
4. AWS Lambda processes the backend business logic.
5. Product and order data are stored in Amazon DynamoDB.
6. Amazon Cognito handles user registration and authentication.
7. CloudFront delivers the website content efficiently to users.
 
Key Features

- Serverless frontend hosting using Amazon S3
- Fast content delivery using Amazon CloudFront
- API-based backend using Amazon API Gateway
- Serverless backend processing using AWS Lambda
- NoSQL database using Amazon DynamoDB
- Secure user authentication using Amazon Cognito
- Scalable and cost-effective cloud architecture

Project Objective

The main objective of this project is to build a scalable and secure e-commerce web application using serverless AWS services.

The project demonstrates how frontend hosting, APIs, backend processing, database storage, content delivery, and user authentication can work together without managing traditional servers.

Technologies Used

- AWS Cloud
- Amazon S3
- Amazon CloudFront
- Amazon API Gateway
- AWS Lambda
- Amazon DynamoDB
- Amazon Cognito
- HTML
- CSS
- JavaScript

Conclusion

This project demonstrates how a complete e-commerce web application can be built using serverless AWS services. The architecture reduces server management and provides a scalable, flexible, and cost-effective approach for hosting an online application.
