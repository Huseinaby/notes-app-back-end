# Notes App Back-End

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Hapi.js-000000?style=for-the-badge&logo=hapi&logoColor=white" alt="Hapi.js">
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint">
</p>

A simple RESTful API for managing notes, allowing users to perform basic CRUD (Create, Read, Update, Delete) operations.  
This project was developed as part of the **Dicoding Back-End Class Submission** for *Belajar Membuat Aplikasi Back-End untuk Pemula*.

The application is built with **Node.js** and the **Hapi.js** framework, with data stored in-memory using a local array (no database).

---

## Key Features

- **Add a New Note**: Create and save a note with title, tags, and body.  
- **Get All Notes**: Retrieve a list of all stored notes.  
- **Get Note by ID**: Fetch the details of a specific note by its unique ID.  
- **Update Note Data**: Edit the content of an existing note.  
- **Delete a Note**: Remove a note from the collection.  

---

## Tech Stack

- **Runtime Environment**: Node.js  
- **Web Framework**: Hapi.js  
- **Unique ID Generation**: nanoid  
- **Code Linter**: ESLint  
- **Development Tools**: Nodemon  

---

##  Installation & Setup

Follow these steps to get the project running on your local machine.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Huseinaby/Bookshelf-API.git
    cd Bookshelf-API
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Run server:**
    ```bash
    npm run start
    ```
    The API will be available at `http://localhost:5000`.

## API Endpoints

| Method   | Endpoint       | Description        |
| :------- | :------------- | :----------------- |
| `POST`   | `/notes`       | Add a new note     |
| `GET`    | `/notes`       | Get all notes      |
| `GET`    | `/notes/{id}`  | Get a note by ID   |
| `PUT`    | `/notes/{id}`  | Update a note by ID|
| `DELETE` | `/notes/{id}`  | Delete a note by ID|
