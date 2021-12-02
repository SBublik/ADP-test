INTRODUCTION :

A JavaScript (nodejs) application that makes an HTTP GET request to https://interview.adpeai.com/api/v1/get-task and then, using the ID and properties returned, dynamically perform the calculation as instructed.

Once you have your ID and your result, make an HTTP POST request to https://interview.adpeai.com/api/v1/submit-task with a JSON POST body including the property ID and result.

The submit-task endpoint will return as follows:

200 : Success;

400: Incorrect value in result; no ID specified; value is invalid

500: ID cannot be found

INSTALLATION :

'npm install' command at the root directory of the project would install all the dev dependencies.

EXECUTION :

'npm start' command at the root directory of the project will start the application.

TESTING :

'npm test' command would run tests across all the files in this project.
