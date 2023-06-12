## Book-Finder
The Google Books Search Engine is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js) with a React front end, MongoDB database, and Node.js/Express.js server and API. It utilizes the Google Books API to allow users to search for books, view details about them, and save books to their account for future reference. This project demonstrates the migration from a RESTful API to a GraphQL API using Apollo Server.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Features](#features)
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
  
## Usage
Follow the instructions provided on the application's user interface to search for books, create an account, save books to your account, view your saved books, and perform other actions based on the acceptance criteria mentioned above.
  
## Features 
* Search for Books: Users can enter search terms and click the submit button to search for books.
  
* Login/Signup: Users can log in or sign up for an account using their email address and password.
  
* Authentication: The application provides authentication functionality to ensure secure access to user-specific features.
  
* Search Results: When users perform a search, the application presents several search results with details such as book title, author, description, image, and a link to the book on the Google Books site.
  
* Save Books: Logged-in users can save books to their account for future reference.
  
* View Saved Books: Users can access a list of books they have saved, displaying the book's details and providing a link to the book on the Google Books site.
  
* Remove Saved Books: Users can remove books from their saved list.
  
* Logout: Users can log out of the application to end their session.
  
## Contributing
Contributions to book-finder are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository or submit a pull request.

## License
This project is licensed under the MIT License.
