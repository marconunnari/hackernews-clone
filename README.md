# Hackernews clone

A clone of [hackernews](https://en.wikipedia.org/wiki/Hacker_News) built with React, Node.js and GraphQL following the tutorials on https://howtographql.com

https://user-images.githubusercontent.com/12419038/163018461-16c8f234-1f79-4cb6-96d7-47cc367462f0.mov


## Technologies

Built with the following technlogies and libraries

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [GraphQL](https://www.graphql.com/)
- [Prisma](https://www.prisma.io/)
- [SQLite](https://sqlite.org/)
- [Apollo server](https://www.apollographql.com/)
- [React router](https://reactrouter.com/)


## Features

- [x] Users can signup, login and logout
- [x] Usars can post a new link
- [x] Users can upvote a link
- [x] Users can see the posted links
- [x] Users can search links with specific terms
- [x] When a link is created or upvoted all users present on the website will get the updated data in real time

## Development

- Clone the repo: `git clone https://github.com/marconunnari/hackernews-clone`

- Open a new tab in your terminal and go to the backend folder: `cd [your project directory]/backend`

- Install the dependencies: `yarn`

- Migrate the database: `yarn prisma migrate dev`

- Start the server: `yarn start`

- Open a new tab in your terminal and go to the frontend directory: `cd [your project directory]/frontend`

- Install the dependencies: `yarn`

- Start the server: `yarn start`

- Go to `http://localhost:3000`
