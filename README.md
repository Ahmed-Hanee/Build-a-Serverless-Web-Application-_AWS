# Build-a-Serverless-Web-Application_AWS
AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito



 ![Architecture overview](https://github.com/AhmedAAst/Build-a-Serverless-Web-Application-_AWS/assets/95107740/900d46ce-d8ce-4603-976a-950420b6c7ec)



# Overview

In this tutorial, you will create a simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet. The application will present users with an HTML-based user interface for indicating the location where they would like to be picked up and will interact with a RESTful web service on the backend to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.

# Prerequisites

To complete this tutorial, you will need an AWS account, AWS CLI installed, an account with ArcGIS to add mapping to your app, a text editor, and a web browser. If you don't already have an AWS account, you can follow the Setting Up Your AWS Environment getting started guide for a quick overview.

# Application architecture

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.


# 1) Static Web Hosting 
  AWS Amplify hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.

  ![image](https://github.com/AhmedAAst/Build-a-Serverless-Web-Application-_AWS/assets/95107740/c1f532c3-dee9-4df1-8594-2217a1b58d19)


# 2) User Management
Amazon Cognito provides user management and authentication functions to secure the backend API.

![image](https://github.com/AhmedAAst/Build-a-Serverless-Web-Application-_AWS/assets/95107740/04ebb66c-cf4d-494d-b5e6-07b45f747885)


# 3)Serverless Backend
Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

![image](https://github.com/AhmedAAst/Build-a-Serverless-Web-Application-_AWS/assets/95107740/bd78aa2b-b4d3-4d5b-9038-5b004a2eeaba)


# 4)RESTful API
JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway

![image](https://github.com/AhmedAAst/Build-a-Serverless-Web-Application-_AWS/assets/95107740/600afca8-1ac5-41d8-acf7-7737b204f84d)
