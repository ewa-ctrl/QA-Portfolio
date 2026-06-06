# API-001: Get All Posts
## Test Case ID
API-001
## Objective 
Verify that the API returns a list of posts.
## Method 
GET
## Endpoint
https://jsonplaceholder.typicode.com/posts
## Preconditions
API is available .
## Test Steps

1.Open Postman

2.Create a GET request

3.Enter endpoint URL

4.Click Send

## Expected Result

-Status code is 200 OK

-Response body contains a list of posts

-Each post contains:

-User ID

-ID

-Title

-body

## Actual Result
Status code is 200 OK returned. Response contains a list of posts.
## Status 
Passed
## Tested Tool
Postman
## Evidence
Screenshot from Postman showing successful execution

![API Test Screenshot](Screenshots/API-001_GET_All_Posts.png)
