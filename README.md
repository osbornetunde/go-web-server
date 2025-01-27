### A simple Go webserver for user mangement

1. Add a user: `POST /users`
2. Get a user: `GET /users/{id}`
3. Delete a user: `DELETE /users/{id}`
4. Update a user: `PUT /users/{id}`

#### Payload format
```json
{
    "name": "John Doe"
} 
```