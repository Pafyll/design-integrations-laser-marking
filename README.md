# Laser Marking integration designs
A repo to store API integration designs for our laser etching hardware and processes.

## Structure

The folders' path structure represents the routes of the proposed endpoints and their HTTP method. All paths will be preceded by: `<BASE_URL>/api/`. 
`BASE_URL` to be confirmed in due course. 

## Workflows

### Requesting new codes

The client app in the warehouse makes a request to our application for N new codes. Our backend application responds with those codes.

### Confirming successful marking

The client app confirms which codes have been successfully marked onto containers by sending a request for the backend to update the database. Our backend application should respond to say whether it updated the containers successfully as marked or not.
