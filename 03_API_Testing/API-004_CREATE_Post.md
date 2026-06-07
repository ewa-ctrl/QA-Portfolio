# API-004: Create Post
## Test Case ID
API-004
## Objective
Verify that a new post can be created  successfully.
## Method 
POST
## Endpoint
https://jsonplaceholder.typicode.com/posts
## Precodnitions
API is available
## Test Steps

1.Open Postman

2.Create a POST request

3.Enter endpoint URL

4.Select Body → raw → JSON

5.Enter request body

6.Click Send

## Actual Result
Status Code 201 Created returned.
Response contains:

-title

-body

-userId

-id

## Status
Passed
## Tested Tool
Postman
## Evidence 
Screenshot form postman showing successful POST request.
