
## Description  
This project involves refactoring a fully functioning Google Books API search engine into a GraphQL API using Apollo Server. The original app was built with the MERN stack, utilizing React on the front end, MongoDB for the database, and a Node.js/Express.js server. It allows users to search for books and save their searches to the back end. The goal of this project is to demonstrate proficiency in refactoring existing RESTful APIs into a more modern, performant GraphQL setup while maintaining the core functionality of the app.

## Motivation  
The motivation for this project stems from the increasing importance of GraphQL in modern web development. As user demands evolve, applications need to be more performant and capable of delivering personalized data efficiently. This project will help enhance skills in both GraphQL and Apollo Server, two technologies that are becoming integral to web development. By refactoring a RESTful API to GraphQL, the project demonstrates how to improve data handling and optimize queries for better performance.

## Purpose  
The purpose of this project is to refactor a Google Books API search engine that was originally built with a RESTful API into a more efficient GraphQL API. The portfolio showcases your ability to work with GraphQL and Apollo Server while highlighting the use of the MERN stack in a real-world application. This project can serve as a strong addition to a web developer's portfolio, demonstrating not only front-end React skills but also server-side expertise in API development.

## Problem Solved  
Traditional RESTful APIs often face performance challenges when handling large sets of data or making multiple requests. This project addresses these issues by:  
- Refactoring the existing RESTful API to GraphQL, which reduces the number of requests and allows clients to request exactly the data they need.  
- Implementing Apollo Server to handle GraphQL queries, making the API more efficient and flexible.  
- Retaining the core functionality of the app, such as allowing users to search for books and save their searches to the database.

## Lessons Learned  
Through this project, I gained experience in:  
- Refactoring an existing application to switch from a RESTful API to a GraphQL API.  
- Using Apollo Server to set up a GraphQL API and manage queries and mutations.  
- Connecting a MongoDB database with Apollo Server to store and retrieve data.  
- Optimizing API performance by reducing unnecessary data fetching through GraphQL queries.  
- Enhancing the user experience by delivering personalized data in a more efficient manner.

## Table of Contents  
- [Installation](#installation)  
- [Usage](#usage)  
- [Credits](#credits)  
- [License](#license)  
- [Features](#features)  
- [How to Contribute](#how-to-contribute)  
- [Tests](#tests)  

## Render  
```bash  
https://two1-searchengine.onrender.com
```  

## Installation  
To set up this project on your local machine, follow these steps:  

1. Clone the repository to your local machine:  
   ```bash  
   git clone https://github.com/danielsantana9824/21-SearchEngine  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd google-books-graphql  
   ```  
3. Install the required dependencies:  
   ```bash  
   npm install  
   ```  
4. Start the development server:  
   ```bash  
   npm start  
   ```  

## Usage  
Once the application is running, you can access it in your browser. The app includes:  
- A search feature to find books using the Google Books API, now powered by GraphQL.  
- The ability to save book searches to the back end, which is stored in the MongoDB database.  
- A user-friendly interface built with React that displays book results dynamically.

### Example Screenshot  
![screenshot](./images/screenshot.png)  

## Credits  
This project builds upon skills and techniques learned in web development courses. React, MongoDB, Apollo Server, and GraphQL were key technologies used in this refactor.  

## License  
This project is licensed under the MIT License. For more information about licenses, please refer to [Choose a License](https://choosealicense.com/).  

## Features  
- Refactored from a RESTful API to GraphQL using Apollo Server.  
- Allows users to search for books via GraphQL queries.  
- Book searches are saved to a MongoDB database for later access.  
- Optimized API performance by minimizing data fetching and reducing unnecessary requests.  
- User-friendly React interface that displays search results dynamically.

## How to Contribute  
If you would like to contribute to this project, fork the repository and submit pull requests. Ensure that you adhere to coding standards and provide meaningful descriptions for your changes.  

Refer to the [Contributor Covenant](https://www.contributor-covenant.org/) for contribution guidelines.  

## Tests  
To run tests for this application, use the following command:  
```bash  
npm run test  
```  

Ensure your testing environment is set up properly and include any additional instructions here if necessary.

