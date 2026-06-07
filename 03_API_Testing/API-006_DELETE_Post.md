# API-006: Delete Post
## Test Case ID
API-006
## Objective
Verify that an existing post can be deleted successfully.
## Method
DELETE
## Endpoint
https://jsonplaceholder.typicode.com/posts/1
## Preconditions
API is avilable
## Test Steps

1.Open Postman

2.Create a DELETE request

3.Enter Ednpoint URL

4.Click Send

## Expected Result
-Status code is 200 OK

Response body is empty or contains empty object
## Actual Result
Status code 200 OK returned

Response body is empty
## Status
Passed 
## Tested Tool
Postman
## Evidence
Screenshot from Postman showing successful DELETE request
