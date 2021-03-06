# Project #3. RESTful Web API with Express.js (a Node.js Framework)

This is Project 3, RESTful Web API with Express.js (a Node.js Framework), in this project I have created an API for the private blockchain and exposed functionality that can be consumed by several types of web clients ranging from desktop, mobile, and IoT devices. The API project required two endpoints:

GET block\
POST block

## Udacity Review
https://review.udacity.com/#!/reviews/1783748

## Pre-requisites

* NodeJS (v10.15 or above recommended)
* Framework: ExpressJS (check "Setup project" instructions below)
* API endpoints documentation: https://documenter.getpostman.com/view/6171412/S1EKzfdD

## Setup project for Review.

To setup the project for review do the following:
1. Download/Clone the project.
2. Run command __npm install__ to install the project dependencies.
3. Run command __npm run start-auto-dump__ in the root directory OR __npm start__ (if you don't want auto block creation).

## Testing the project

In order to test the functionality you could use the following tools:

1. Postman
* use API endpoints documentation https://documenter.getpostman.com/view/6171412/S1EKzfdD
* send GET and POST requests (make sure to run the command `npm start` OR `npm run start-auto-dump` and keep the server running)

2. cURL
* GET
`curl -X GET \
  http://localhost:8000/api/block/2 \
  -H 'cache-control: no-cache'
`

* POST
`
curl -X POST \
  http://localhost:8000/api/block/ \
  -H 'Content-Type: application/json' \
  -H 'cache-control: no-cache' \
  -d '{
    "body": "Adding new block"	
}'
`

## What did I learn with this Project

* I was able to create a RESTful API using variety of Node.js Frameworks for a Blockchain application.
