# User API Spec

## Register User

Endpoint : POST /api/users

Request Body :

```json
{
  "username": "Haikal",
  "password": "rahasia",
  "name": "Ahmad Fikri Haikal"
}
```

Response Body (Success) :

```json
{
  "data": {
    "username": "Haikal",
    "name": "Ahmad Fikri Haikal"
  }
}
```

Response Body (Failed) :

```json
{
  "error": "Username must not blank!"
}
```

## Login User

## Get User

## Update User

## Logout User
