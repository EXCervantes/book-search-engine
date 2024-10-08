# Book Search Engine

## Table of Contents

- [Book Search Engine](#book-search-engine)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Technologies and Packages Used](#technologies-and-packages-used)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Link to Deployed Application](#link-to-deployed-application)
    - [Screenshots of the Application](#screenshots-of-the-application)
  - [Credits](#credits)
  - [License](#license)

## Description

This application uses the Google Books API along with GraphQL API built with the Apollo Server to allow users to save book searches to the back end. Originally built using a RESTful API paradigm this project has been refactored using a GraphQL API in the MERN structure.

The application uses [Express.js](https://expressjs.com/) for handling the server, the [Mongoose](https://mongoosejs.com/) for interaction with [MongoDB](https://www.mongodb.com/docs/atlas/), [Apollo Client](https://www.apollographql.com/docs/react/) to manage data in [GraphQL](https://graphql.org/), and [React.js](https://react.dev/) to build the application on the front end. The [Node language manager](https://expressjs.com/) uses those packages to build and run the application.

This project is deployed to [Render Dashboard](https://dashboard.render.com/) as an app which can be used in the browser.

## Technologies and Packages Used

- [Node.js](https://nodejs.org/en)
- [Express.js](https://expressjs.com/)
- [React.js](https://react.dev/)
- [MongoDB](https://www.mongodb.com/docs/atlas/)
- [Mongoose](https://mongoosejs.com/)
- [Apollo Client](https://www.apollographql.com/docs/react/)
- [GraphQL](https://graphql.org/)
- [Google Books API](https://developers.google.com/books/docs/overview)
- [Concurrently](https://www.npmjs.com/package/concurrently)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [JWT](https://jwt.io/introduction)
- [Render Dashboard](https://dashboard.render.com/)
  
## Installation

This is a full functioning application deployed at [this link](https://book-search-engine-c3e9.onrender.com/).

Alternatively, a user can clone the repository to view it on their local machine. Run `npm install` to install the necessary dependencies for the page to work. Initialize the application by using `npm run develop` to run both server and client side directories locally.

## Usage

Once the page is open a user can search for their book in the search bar. The app will return results matching the searched title and related titles with a book cover picture, title of book, author(s), and description. Selecting "Login/Sign Up" will display a box where the options to either log in or sign up will be found. For signing up enter a username, email, and password. For logging in enter an email and password used to create an account.

If the user creates an account or logs in, the option to save a book will become available below a book's description. In addition, "See Your Books" will display a user's saved books with the option to delete a book from the saved books list. Selecting logout will log the user out of the current session.

### Link to Deployed Application

Follow [this link](https://book-search-engine-c3e9.onrender.com/) to visit this application's page.

### Screenshots of the Application

![Book Search Logged Out](/client/src/assets/images/book-search-screen1.jpg)
![Book Search Logged In](/client/src/assets/images/book-search-screen2.jpg)
![Saved Books](/client/src/assets/images/book-search-screen3.jpg)

## Credits

The following two articles referenced for how to handle an input type under Mutations in the typeDefs.js

_javascript - GraphQL: Use input type and one of its fields in the same query - Stack Overflow_. (2020, February 23). Stack Overflow. Retrieved August 23, 2024, from https://stackoverflow.com/questions/60365959/graphql-use-input-type-and-one-of-its-fields-in-the-same-query

_What's the point of input type in GraphQL? - Stack Overflow_. (2019, April 27). Stack Overflow. Retrieved August 23, 2024, from https://stackoverflow.com/questions/41743253/whats-the-point-of-input-type-in-graphql
  
## License

This project is licensed under [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Please see the [License](https://opensource.org/licenses/MIT) page for more info.
