# LBB_UEK295
The "taskManager" API allows users to manage their tasks effectively through a series of HTTP endpoints that support creating, retrieving, updating, and deleting tasks. This Project was created for "ZLI 
Leistungsbeurteilung: Element B Abgabe"
## Features
+ User Authentication: Supports login and logout functionalities.
+ CRUD Operations: Users can create, read, update, and delete tasks.
+ API Documentation: Integrated Swagger UI based on the OpenAPI specification.
+ Session Management: Manages user sessions with cookie-based authentication.
## NPM Dependencies
+ express: Framework for handling and routing HTTP requests.
+ body-parser: Middleware to parse incoming request bodies.
+ swagger-ui-express: Middleware to serve the Swagger UI bound to your Swagger document.
+ express-session: Middleware to manage sessions.
+ cookie-parser: Middleware to parse cookies attached to the client request object.
+ express-openapi-validator: Middleware for request and response validation based on the OpenAPI specification.
+ fs: Node.js core module to handle the file system.
+ yaml: Module to parse YAML files.