# Task Tracker

Welcome to the Task Tracker application. This application allows you to add, delete, and view tasks.

## Installation

1. Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.
2. Clone this repository or download the source code.
3. Open a terminal in the root directory of the project and run the following command to install the required dependencies:

npm install

## Running the application

### Step 1: Start the JSON server

npm run backend

This will start a local JSON server that serves as the mock backend for the application. The server will be running on port 5000 and will watch the db.json file for changes.

### Step 2: Start the Vue.js development server

npm run serve

This will start a development server for the application and will open the application in your default browser. You can now interact with the application on http://localhost:8080.

### Note

- The json-server is a mock backend, so all the data will be lost when you stop the json-server.

Thank you for trying out the Task Tracker application!
