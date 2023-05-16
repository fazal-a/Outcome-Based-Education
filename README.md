# Outcome-Based Education

This repository contains the source code for the Outcome-Based Education (OBE) project, which consists of both a client and a server component.

## Client

The client folder contains the Angular-based client application for the OBE project. The client application allows users to interact with the OBE system and perform various tasks.

### Dependencies

To install the dependencies for the client application, navigate to the client folder and run the following command:


The client application has the following dependencies:

- Angular
- Bootstrap
- ng-bootstrap
- FileSaver
- jQuery
- Material Icons
- ngx-cookie-service
- ngx-toastr
- pdfmake
- rxjs
- xlsx
- zone.js

### Scripts

The available scripts for the client application are:

- `start`: Starts the development server for the client application.
- `build`: Builds the client application for production.
- `watch`: Builds the client application and watches for changes in development mode.
- `test`: Runs the unit tests for the client application.

## Server

The server folder contains the Node.js server application for the OBE project. The server application provides the backend functionality required for the client application to interact with the database and perform various operations.

### Dependencies

To install the dependencies for the server application, navigate to the server folder and run the following command:


The server application has the following dependencies:

- bcrypt
- cors
- dotenv
- express
- ldapjs
- mongoose
- morgan
- nodemon

### Scripts

The available scripts for the server application are:

- `start`: Starts the server using nodemon, which automatically restarts the server when changes are made.
- `test`: Runs the tests for the server application.

## Usage

To use the Outcome-Based Education system, follow these steps:

1. Clone this repository to your local machine.
2. Install the dependencies for both the client and server applications as described above.
3. Start the server application by running the command `npm start` in the server folder.
4. Start the client application by running the command `npm start` in the client folder.
5. Access the client application by opening a web browser and navigating to the provided URL (usually `http://localhost:4200`).

Feel free to explore the code and make any modifications or improvements as needed.

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.

## Author

This project was created by Fazal Abbas
