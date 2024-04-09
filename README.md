# Blog Application

A blog application project built with React, Redux Toolkit, Styled Components, Axios, Node.js, Express, and MongoDB.
![Blog Application Screenshot](/images/home.png)


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Images](#images)

## Overview

This project is a blog application that allows users to create, read, update, and delete blog posts. Users can sign up for an account, create posts, view posts created by other users, and interact with them by liking and commenting. The application provides a seamless and responsive user interface for a pleasant blogging experience.


## Features

- User authentication (sign up, sign in, sign out) using JWT tokens.
- CRUD operations for blog posts.
- Like and comment functionality for posts.
- Responsive design for seamless experience across devices.


## Usage
- Sign up for an account or sign in with an existing account.
- Create new blog posts.
- View existing blog posts.
- Edit or delete your own blog posts.
- Sign out when done.
## Technologies Used
- React
- Redux Toolkit
- Styled Components
- Axios
- Node.js
- Express
- MongoDB


## Setup

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/tejesh99999/blog-application.git

2. Install dependencies:

   ```bash
   cd blog-application
   npm install

3. Set up MongoDB:
- Make sure MongoDB is installed and running on your system.
- Create a MongoDB database and configure the connection in server/config/db.js.


4. Start the development server and client:

    ```bash 
    cd ../server
    node index.js
  
    cd ../client
    npm start


## Images
### Log-In page
![Blog Application Screenshot](/images/login.png)
### Blog page
![Blog Application Screenshot](/images/blog.png)


