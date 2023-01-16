Task Tracker
Welcome to the Task Tracker application. This application allows you to add, delete, and view tasks.

Installation
Make sure you have Node.js and npm installed on your machine.
Clone this repository or download the source code.
Open a terminal in the root directory of the project and run the following command to install the required dependencies:
Copy code
npm install
Running the application
In the terminal, run the following command to start the JSON server:
Copy code
npm run backend
This will start a local JSON server that serves as the mock backend for the application. The server will be running on port 5000 and will watch the db.json file for changes.

In another terminal window, run the following command to start the development server for the Vue.js application:
Copy code
npm run serve
This will start a development server for the application and will open the application in your default browser. You can now interact with the application on http://localhost:8080.

You should now be able to interact with the application.
Note
The json-server is a mock backend, so all the data will be lost when you stop the json-server.
Thank you for trying out the Task Tracker application!
