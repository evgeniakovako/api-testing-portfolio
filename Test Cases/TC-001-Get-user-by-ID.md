# TC-001 Get user by ID

## Preconditions
API is available.

## Endpoint
GET /users/1

Base URL:
https://jsonplaceholder.typicode.com

## Test Steps
1. Open Postman.
2. Select the GET method.
3. Enter the URL:
   https://jsonplaceholder.typicode.com/users/1
4. Click **Send**.

## Expected Result
- Status code is 200 OK.
- Response is returned in JSON format.
- The field `id` equals `1`.
- The field `name` is present.
- The field `email` is present.


