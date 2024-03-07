
# MERN Todo App

This is a simple todo application built with React, Node, Express, and MongoDB.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

This application allows users to manage their tasks by adding, deleting, and marking them as complete or incomplete.

The frontend is built with React, utilizing hooks like `useState` and `useEffect` for state management and side effects. It communicates with the backend via RESTful API calls.

The backend is powered by Express.js, providing APIs to perform CRUD operations on todo items. MongoDB is used as the database to store todo items.

## Features

- Add new todo items
- Delete existing todo items
- Mark todo items as complete or incomplete

## Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/react-todo-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-todo-app
   ```

3. Install dependencies for both frontend and backend:

   ```bash
   # Install frontend dependencies
   cd client
   npm install

   # Install backend dependencies
   cd ../server
   npm install
   ```

4. Set up MongoDB:
   - Install MongoDB if you haven't already.
   - Start MongoDB service.

5. Configure environment variables:
   - Create a `.env` file in the `server` directory.
   - Define the following variables:
     - `MONGODB_URI`: MongoDB connection URI.
     - `PORT`: Port for the Express server (default is 3001).

6. Seed initial data (optional):
   - If you want to populate the database with initial todo items, you can run a script to seed data.

## Usage

To start the application, follow these steps:

1. Start the backend server:
   ```bash
   cd server
   npm start
   ```

2. Start the frontend development server:
   ```bash
   cd client
   npm start
   ```

3. Access the application in your web browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or new features you'd like to see.
