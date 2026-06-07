# API-003: Get Non-Existing Post
## Test Case ID
API-003
## Objective
Verify API behavior when requesting a non-exiting post.
## Method 
GET
## Endpoint
https://jsonplaceholder.typicode.com/posts/999999
## Preconditions
API is available
## Test Steps

1.Open Postman

2.Create a GET request.

3.Enter endpoint URL.

4.Click Send.

## Expected Result
-Status Code 404 Not Found

-Response body is empty and does not contain post data.
## Actual Result
Status Code 404 Not Found returned
Response body is empty and does not contain post data
## Status
Passed
## Tested Tool
Postman
## Evidence
Screen shot from postman showing response for non-existing post.

