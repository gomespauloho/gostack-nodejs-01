# The first module from nodeJS
Users API

## Execution

### Resolve dependences
```bash
yarn
```

### Execute the project
```
yarn dev
```

## API

### Routes

- /users

### Definitions
- GET all users
  - Returns an array of users
  - Url example: http://localhost:3000/users
- GET specific user
  - Array index is required in route parameters
  - Returns an array of users
  - Url example: http://localhost:3000/users/1
- POST
  - Create user
  - Returns an array of users
  - The ```name``` property is required in the json body
  - Url example: http://localhost:3000/users
- PUT
  - Alter user
  - Returns an array of users
  - Array index is required in route parameters
  - The ```name``` property is required in the json body
  - Url example: http://localhost:3000/users/1
- DELETE
  - Delete user
  - Array index is required in route parameters
  - Url example: http://localhost:3000/users/1