# LBB_UEK295
The "taskManager" API allows users to manage their tasks effectively through a series of HTTP endpoints that support creating, retrieving, updating, and deleting tasks.<br />
This Project was created by Roan Ratering for the "ZLI Leistungsbeurteilung: Element B Abgabe"
## Features
+ User Authentication: Supports login and logout functionalities.
+ CRUD Operations: Users can create, read, update, and delete tasks.
+ API Documentation: Integrated Swagger UI based on the OpenAPI specification.
+ Session Management: Manages user sessions with cookie-based authentication.
## Prerequisites
Ensure that Node.js is installed on your system. Download it from the Node.js official website.
## Installation
Clone the repository to your machine and install the dependencies:<br />
```git clone https://github.com/Chistebueb/LBB_UEK295```<br />```cd LBB_UEK295```<br />```npm install```
## Running the Application
To start the application, run:<br />

```node scripts/taskManager.js```<br />
The server starts on port 3000 by default.

## NPM Dependencies
+ express: Framework for handling and routing HTTP requests.
+ body-parser: Middleware to parse incoming request bodies.
+ swagger-ui-express: Middleware to serve the Swagger UI bound to your Swagger document.
+ express-session: Middleware to manage sessions.
+ cookie-parser: Middleware to parse cookies attached to the client request object.
+ express-openapi-validator: Middleware for request and response validation based on the OpenAPI specification.
+ fs: Node.js core module to handle the file system.
+ yaml: Module to parse YAML files.<br />
```npm install express body-parser swagger-ui-express express-session cookie-parser express-openapi-validator fs yaml```
## API Documentation
View the API documentation through the Swagger UI:<br />
```http://localhost:3000/api-docs```