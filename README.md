# Dhivya-notes-backend

# Node.js CRUD Application with MongoDB

This is a simple Node.js application that demonstrates CRUD (Create, Read, Update, Delete) operations on notes using MongoDB as the database.

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js: [Download and Install Node.js](https://nodejs.org/)
- MongoDB: [Install MongoDB](https://docs.mongodb.com/manual/installation/)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/Dhivya0591/notes-backend.git
    cd notes-backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Configure MongoDB:

    - Create a MongoDB database.
    - Update the database connection details in index.js file.

4. Run the application:

    ```bash
    npm start
    ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to access the application.

## Usage

The application provides endpoints for performing CRUD operations on notes. Below are the available routes:

- **GET api/notes**: Retrieve all notes.
- **GET api/notes/:id**: Retrieve a specific note by ID.
- **POST api/notes**: Create a new note.
- **PUT api/notes/:id**: Update a note by ID.
- **DELETE api/notes/:id**: Delete a note by ID.
