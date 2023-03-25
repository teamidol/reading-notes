# **301 READING CLASS 12**

## **STATUS CODES BASED ON REST METHODS**

* Some status codes..

100 Some delay due to processing.

200 Request went through, here's the status.

300 Redirect.

400 Cannot proceed, client error.

500 Server error.

* Status code 202 is "accepted."

* Status code 308 is "permanent redirect."

* A 406 "not acceptable" would be used if an update didn't return data to a client.

* A 410 code would be used if a resource used to exist but no longer does.

* A *forbiddden* status means a client has no permission to access the resource.

## **BUILD A REST API WITH NODE.JS & MONGODB - QUICK**

* We don't want to use something that's not our localhost so we need to pull the MongoDB database string out of our server.js and put it in .env file.

* A *middleware* is a code that runs when the server does a request but before it's passed down to the routes.

* app.use(express.json()) allows server to use json formatted files.

* /:id in a route, with the colon, means it's a parameter that can be accessed with request *.param.*

* The difference between PUT and PATCH, PUT updates everything but PATCH updates specific contents.

* To make a default value in schema just have "default:"

* A 500 error status code means the error is a server error.

* Status code 200 means read request is successful. Status 201 means what was created was successful.



:thinking: ##Things I want to know more about. 