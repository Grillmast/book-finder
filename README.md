## Book-Finder
The Google Books Search Engine is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js) with a React front end, MongoDB database, and Node.js/Express.js server and API. It utilizes the Google Books API to allow users to search for books, view details about them, and save books to their account for future reference. This project demonstrates the migration from a RESTful API to a GraphQL API using Apollo Server.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Technologies Used](#technologies used)
* [Contributing](#contributing)
* [License](#license)
## Installation
To install and run this application locally, follow these steps:

Clone the repository:
Copy code:
```
git clone <repository-url>
```
Navigate to the project directory.

Copy code
```
cd <project-directory>
```
Install the required dependencies.

Copy code
```
npm install
```
Set up the environment variables.

Create a .env file in the root directory of the project.

Add the following environment variables to the file:

Copy code
```
MONGODB_URI=<your-mongodb-uri>
SECRET=<your-secret-key>
```
Replace <your-mongodb-uri> with the MongoDB connection URI for your database.
Replace <your-secret-key> with a secret key of your choice for session encryption.

Start the application.

Copy code
```
npm start
```
Open your web browser and visit http://localhost:3000 to access the application.
