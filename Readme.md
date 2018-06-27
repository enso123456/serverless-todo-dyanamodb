# Serveless Lambda NodeJS

A Todo Rest API using serveless lambda function and storing data using DynamoDB.

## Tools/Frameworks

* [Serverless](https://serverless.com/)
* [Nodejs](https://nodejs.org/en/)
* [DynamoDB](https://console.aws.amazon.com/dynamodb/)

## Setup

* Clone the repository
* Setup your `serverless config credentials --provider provider --key key --secret secret`
* Run `sls deploy`

## Endpoints

* POST - https://[api-url-generated].execute-api.us-east-1.amazonaws.com/dev/todos
* GET - https://[api-url-generated].execute-api.us-east-1.amazonaws.com/dev/todos
* GET - https://[api-url-generated].execute-api.us-east-1.amazonaws.com/dev/todos/{id}
* PUT - https://[api-url-generated].execute-api.us-east-1.amazonaws.com/dev/todos/{id}
* DELETE - https://[api-url-generated].execute-api.us-east-1.amazonaws.com/dev/todos/{id}


