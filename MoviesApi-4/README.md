## Bomb - 3

### Problem
User cannot save a new user even though they recieve a 200

### Steps to recreate
- send post http request to http://localhost:8080/users
- recieve 200
- don't see new user info when fetching all or by id
### Expected behaviour
- send post http request to http://localhost:8080/users
- recieve 200
- be able to access new user data in get all or by id
### Goal
achieve expected behaviour
