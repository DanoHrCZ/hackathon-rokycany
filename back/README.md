---
runme:
  id: 01HNCN5CAG28Z4Y1J84XB5R9EH
  version: v2.2
---

# Back
## API
v1 - Ful open<br>
v2 - Protected by jwt<br>

api/v1/auth:<br>
api/v1/auth/reg POST<br>
api/v1/auth/log POST<br>
<!-- api/v1/auth/reg POST -->

api/v2/work:<br>
api/v2/work/ GET<br>
api/v2/work/ POST<br>
api/v2/work/:id GET<br>
api/v2/work/:id PUT<br>
api/v2/work/:id DELETE<br>

api/v2/workRequests:<br>
api/v2/workRequests/ GET<br>
api/v2/workRequests/ POST<br>
api/v2/workRequests/:id GET<br>
api/v2/workRequests/:id PUT<br>
api/v2/workRequests/:id DELETE<br>

## API REQUESTS
### JWT token
```
claims {

}

Header: Authorization
How looking: Bearer qwkeljqlwje.lqwekjqwlje.qweojqwoej
```
### Auth
api/v1/auth/reg POST
Type | JSON |
Request | {"username": "name", "password": "something", "email": "admin@gmail.com"} |
Response | {"status"} |
Error response | {"status": "ok"} | 


api/v1/auth/log POST
Type | JSON 
Request | {"username": "name", "password": "something"} 
Response | {"token": "qweljqwlejo123uj.oodjwoi1j2320j.1230udwq"}
Error response | {"status": "ok"}

### Work
### WorkRequests