### A simple Go webserver for user mangement

1. Add a user: `POST http://localhost:8080/users`
2. Get a user: `GET http://localhost:8080/users/{id}`
3. Delete a user: `DELETE http://localhost:8080/users/{id}`
4. Update a user: `PUT http://localhost:8080/users/{id}`

#### Payload format
```json
{
    "name": "John Doe"
} 
```