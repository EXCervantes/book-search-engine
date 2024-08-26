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

This application uses the Google Books API along with GraphQL API built with the Apollo Server to allow user to save book searches to the back end. Originally built using a RESTful API paradigm this project has been refactored using a GraphQL API in the MERN structure.

The application uses [Express.js](https://expressjs.com/) for handling the server, the [Mongoose](https://mongoosejs.com/) for interaction with [MongoDB](https://www.mongodb.com/docs/atlas/), [Apollo Client](https://www.apollographql.com/docs/react/) to manage data in [GraphQL](https://graphql.org/). The [Node language manager](https://expressjs.com/) uses those packages to build and run the application.

This project is deployed to [Render Dashboard](https://dashboard.render.com/) as an app which can be used in the browser. In addition, this application can be installed on a local system for offline use.

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

This is a full functioning application deployed at [this link](https://pwa-jate-zgyl.onrender.com/).

Alternatively, a user can clone the repository to view it on their local machine. Run `npm install` to install the necessary dependencies for the page to work. Initialize the application by using `npm run start`.

## Usage

Once the page is open a user can navigate it via the menu at top or the user can scroll down to find the site will load each "page" of the website automatically. Clicking on an image of a project will take the user to that respective project's deployment page. Please note, the form does not currently send a notification upon submission. This will be implemented soon.

### Link to Deployed Application

Follow [this link]() to visit this application's page and install it locally.

### Screenshots of the Application

![App In Browser](images/jate-pwa-screen1.jpg)
![App Running Locally](images/jate-pwa-screen2.jpg)
![Service Worker](images/jate-pwa-screen3.jpg)
![Manifest File](images/jate-pwa-screen4.jpg)

## Credits

N/A
  
## License

This project is licensed under [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Please see the [License](https://opensource.org/licenses/MIT) page for more info.
