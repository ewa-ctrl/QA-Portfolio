# API-002: Get Single Post
## Test Case Id
API-002
## Objective
Verify that the API returns details for a specific post.
## Method
GET
## Endpoint
https://jsonplaceholder.typicode.com/posts/1
## Preconditions
API is available.
## Test Steps

1.Open Postman
2.Create a GET request
3.Enter endpoint URL
4.Click Send
## Expected Result
-Status code is 200 OK
-Response contains a single post
-Response contains:
-UserId
-Id
-Title
-Body
-Id value equals 1
## Actual Result
Status code 200 OK returned.
Response contains details of post with id = 1.
## Status
Passed
## Tested Tool
Postman 
## Evidence
