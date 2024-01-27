# Learning path for Backend with Nodejs:
---
## - Basic Level:
- ECMAScript
- Destructuring
- Template literals
- Http Module

#### Exercises:
1. **Function to break down an Array:** create a function that takes the maximum number, minimum number, total sum, and average.
2. **Basic Http Server:** use the 'http' module to respond with a welcome message that includes the visitor's name using 'template literals'.

---
## - Intermediate Level:
- Import/Export
- 'fs' Module for reading and writing
- Async/Await
- Handling asynchronous errors

#### Exercises:
1. **Importing and exporting modules:** create two modules, one for reading and another for writing files. These modules should use a third file to copy the content from one text file to another.
2. **Async/Await and error handling:** create an asynchronous function that simulates data download from a server. It should receive a URL and return the downloaded data. Implement error handling mechanisms.

---
## - Express JS:
- What it is
- Routes
- Middleware
- Creating a simple web application
- RESTful API

#### Exercises:
1. **Basic routes and middleware:** create an application with main ('/'), about ('/about'), and contact ('/contact') routes that have middleware to log to the console each time a request is made.
2. **Basic RESTful API:** create an API to manage a task list with the following routes:
    1. Get all tasks (GET '/tasks')
    2. Get a task by ID (GET '/tasks/:id')
    3. Add a new task (POST '/tasks')
    4. Update a task by ID (POST '/tasks/:id')

3. **Simulate basic login:**
    1. Registration route (POST '/register'): allows registering users using a username and password using bcrypt.
    2. Login route (POST '/login'): verifies credentials and returns an authentication token.
    3. Protected route (GET '/protected'): uses middleware to protect this route so that only authenticated users can access it.

---
## - Advanced Level:
- CRUD Operations with a database
- Authorization Systems
- User Roles and Permissions
- WebSockets
- Testing
- Security Best Practices

#### Exercises:
1. **CRUD API:** create a RESTful API with Express to manage products connected to a database with an authorization system allowing only specific users to edit the data.
2. **Roles and permissions:** add user and admin roles to the previous exercise and make only certain API routes available to them.
3. **Real-time Chat with WebSockets:** use web sockets with Express JS to send and receive messages between the server and the client.
4. **Testing:** Add integration tests covering API routes and CRUD operations.
5. **Enhance security:** prevent attacks such as SQL injections and XSS. Use tools like Helmet to improve header protection.

---

