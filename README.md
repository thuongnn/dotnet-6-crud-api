# dotnet-6-crud-api

.NET 6.0 - CRUD API Example

### Get all user with curl
```
curl -X GET http://188.166.254.30/users
```
### Get user by id with curl
```
curl -X GET http://188.166.254.30/users/1
```
### Create user with curl
```
curl -X POST http://188.166.254.30/users \
    -H "Content-Type: application/json" \
    -d '{
        "title": "Mr",
        "firstName": "George",
        "lastName": "Costanza",
        "role": "User",
        "email": "george@costanza.com",
        "password": "george-likes-spicy-chicken",
        "confirmPassword": "george-likes-spicy-chicken"
    }'
```
### Update user with curl
```
curl -X PUT http://188.166.254.30/users/1 \
-H "Content-Type: application/json" \
-d '{
    "title": "Mr",
    "firstName": "Thuong",
    "lastName": "Nguyen Nhu",
    "role": "User",
    "email": "thuongnn@gmail.com",
    "password": "george-likes-spicy-chicken",
    "confirmPassword": "george-likes-spicy-chicken"
}'
```
### Delete user with curl
```
curl -X DELETE http://188.166.254.30/users/1

```