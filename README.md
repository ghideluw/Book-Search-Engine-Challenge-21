# Book-Search-Engine-Challenge-21

## Description
The goal of this project was to take a Google Books API search engine that use a Restful API, and refractor it to be a GraphQL API that uses an Apollo Server. 
This application follows the MERN model(MongoDb, Express.js, REACT, and node.js). The user will be able to search and save book queries to the database and 
retrieve that data. The user will be able to sign up and store their account credentials, so they will be able to login and view their searches as well as modify 
them later.
The Apollo server will allow the application the ability to fetch and modify data using queries and mutations from GraphQL. By connecting Apollo Client with React 
with ApolloProvider component, the application will be able to wrap the React app to Apollo Client, allowing Apollo to access React components anywhere on the 
component tree. This application will be deployed using Heroku for user interaction.

## Table of Contents
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Technologies
This application will implement the following technologies:

-MongoDB
-Express.js
-React.js
-Node.js
-JavaScript
-GraphQL API
-Apollo Server
-Heroku

## Installation

To install the application clone the project directory and run "npm install" in the terminal to install all dependencies and packages.

## Usage
After installation, the application requires that you run "npm start development" in the terminal while MongoDB is running to connect the server and API 
with the database. 

## SCREENSHOT ![image](https://user-images.githubusercontent.com/111549689/219942374-87bc4229-456c-4425-9d8c-68a1c47b6140.png)

## License

MIT License

Copyright (c) [2023] [Luwam Ghide]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
