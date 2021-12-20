# Basic API in Node.JS, with a CRUD of Users, using mock instead of a real database.

### Project developed during the course called [JStack](https://jstack.com.br/).

# How to start the server

Write this into the terminal.

```text
node src/index.js
```

and you should see something like that:
```text
🔥 Server started at http://localhost:3000
```

## Endpoints

### List Users
```text
[GET] /users
```

### Create User
```text
[POST] /users
```

```json
{
  "name": "Milton Luiz"
}
```

### Update User
```text
[PUT] /users/:id
```

```json
{
  "name": "Milton Junior"
}
```

### Delete User
```text
[DELETE] /users/:id
```
