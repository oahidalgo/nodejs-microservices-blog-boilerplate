# Node.js Microservices Blog Boilerplate

This project is a boilerplate for creating a blog using microservices with Node.js.

## Features

- Microservices: The application is composed of several independent microservices that communicate with each other through asynchronous events using an event bus.

- Frontend (Client): The frontend of the application is built with React and allows users to create new posts and add comments to existing posts.

- Microservice 1: Posts Service: This microservice is responsible for managing posts. It provides routes to create new posts and retrieve the list of existing posts.

- Microservice 2: Comments Service: This microservice handles comments associated with posts. It allows adding comments to a specific post and retrieving comments for a post.

- Microservice 3: Event Bus: The event bus microservice is responsible for receiving and dispatching events to the other microservices. It provides a way for asynchronous communication between different components of the application.

- Microservice 4: Moderation Service: This microservice is responsible for moderating comments. It checks the content of comments and assigns a status (approved or rejected) based on certain rules. It sends events to inform other microservices about the status of comments.

- Microservice 5: Query Service: The query service microservice handles queries and updates related to posts and comments. It provides a route to retrieve all posts and processes events to keep the post and comment data up to date.

## Prerequisites

- Node.js (version 16.18.X)

## Installation

1. Clone the repository:

git clone https://github.com/oahidalgo/nodejs-microservices-blog-boilerplate.git

2. Install the dependencies for each microservice:

npm install

3. Start each microservice separately. Open a new terminal and navigate to each microservice directory and run the following command:r:

cd <microservice directory>
npm start

5. You're all set! You can now access the application in your browser at http://localhost:3000.


## Contributions

If you wish to contribute to this project, follow these steps:

Fork the repository.
Create a new branch for your changes.
Make the changes and commit your modifications.
Submit a pull request with your changes.






