# bSafe-Web-API
Calhacks 3.0 Project
The Corresponding API to the APP

Receives, processes and returns information to/from the app wrote with JavaScript, MongoDB and hosted on Azure.


Bugs/To DO

Implement the chat function

Implement the calculating route function


List of Http Requests:

GET /users for all users

GET /users/_id for one user

POST /users with user object is to add user

PUT /users/_id with user object is to update a user

DELETE /users/_id to delete user

POST /users/login with email and password is to log in use

GET /requests to get all requests

GET /requests/_id is to get one request by its id

GET /requests/user/_id is to get requests for one user

POST /requests/:userId is to add request to that user

POST /requests to add request (ignore previous one)

PUT /requests/_id, DELETE /requests/_id

GET /matches

GET /matches/_id

GET /matches/request/_id

POST /matches/_id

PUT /matches/_id

DELETE /matches/_id
