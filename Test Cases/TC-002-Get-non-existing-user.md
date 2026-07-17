# TC-002 Get non-existing user

## Preconditions

API is available.

## Endpoint

GET /users/999

Base URL:
https://jsonplaceholder.typicode.com

## Test Steps

1. Open Postman.
2. Select the GET method.
3. Enter the URL:
   https://jsonplaceholder.typicode.com/users/999
4. Click **Send**.

## Expected Result

- Status code is 404 Not Found.
- Response is returned in JSON format.
- Response body is an empty JSON object (`{}`).
