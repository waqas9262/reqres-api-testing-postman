# ReqRes API Testing – Postman

This project contains a Postman collection for testing the public [ReqRes](https://reqres.in/) REST API.

## What’s covered

- `GET /api/users` – List users  
- `POST /api/users` – Create user  
- `PUT /api/users/{id}` – Update user  
- `DELETE /api/users/{id}` – Delete user  

Each request includes:
- Basic test assertions (status code, response body fields)
- Example payloads for positive scenarios

## How to use

1. Download the collection JSON from this repo.  
2. Import it into Postman.  
3. Set the `baseURL` variable in the collection to `https://reqres.in`.  
4. Send individual requests or run the whole collection.

## Future improvements

- Add more negative test cases  
- Add data-driven tests  
- Integrate with Newman + CI (GitHub Actions)
