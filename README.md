# NodeJs restful api with jwt
A simple restful nodejs server with JWT token authorization

## Prerequisites
* NodeJS
* Mongo DB

## Starting server
npm start run

## Test with postman
## Register

/auth/register

Body
fullName, password, email

## Login
/auth/sign_in

Body
email, password

## Create task

/tasks

Header: Authorization JWT {{your_token}}
Method: Post
Body:   name


