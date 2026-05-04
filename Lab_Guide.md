# Web Design and Development: Project Guide

This guide provides the problem statements, execution commands, and guidance for 7 beginner-level full-stack assignments.

---

## General Instructions
1. **Node.js**: Ensure Node.js is installed on your system.
2. **Database**: For projects using MySQL, ensure your MySQL server is running and you have created the necessary databases/tables.
3. **Execution**: Always run the commands from the specific project folder.

---

## 1. Basic Express Server
**Problem Statement**: Create a basic Express server with three routes: `/`, `/status`, and `/info`. Build a frontend with three buttons to fetch data from these routes and display it on the screen.

- **Folder**: `express_assignments/basic-express-server`
- **Commands**:
  ```bash
  cd express_assignments/basic-express-server
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: This project demonstrates basic routing and static file serving. The `index.html` uses `fetch()` to call the backend APIs.

---

## 2. Books REST API
**Problem Statement**: Develop a RESTful API for managing a book collection. Features should include listing all books, adding a new book, and deleting a book.

- **Folder**: `express_assignments/books-rest-api`
- **Commands**:
  ```bash
  cd express_assignments/books-rest-api
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: This uses an in-memory array to store books. The frontend sends JSON data using `POST` to add books and uses `DELETE` to remove them.

---

## 3. Notes API (MySQL)
**Problem Statement**: Build a Notes application that stores data in a MySQL database. Users should be able to provide a title and content to save a note and view a list of all saved notes.

- **Folder**: `backend_mysql_assignments/notes-api-mysql`
- **Commands**:
  ```bash
  cd backend_mysql_assignments/notes-api-mysql
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: Ensure you have a `testdb` database and a `Notes` table with columns `id`, `title`, and `content`. This project shows how to connect Express to MySQL.

---

## 4. Contacts API
**Problem Statement**: Create a contact management system where users can store names, phone numbers, and emails. The system should allow viewing and deleting contacts.

- **Folder**: `backend_mysql_assignments/contacts-api-mysql`
- **Commands**:
  ```bash
  cd backend_mysql_assignments/contacts-api-mysql
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: Uses MySQL for persistent storage. The frontend uses a form to capture user input and standard `fetch` calls to interact with the database.

---

## 5. Products API
**Problem Statement**: Build a product inventory system. Show a list of products and provide a form to update the price and stock of a product by its ID. If an ID is not found, show an error message.

- **Folder**: `backend_mysql_assignments/products-api-mysql`
- **Commands**:
  ```bash
  cd backend_mysql_assignments/products-api-mysql
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: Demonstrates the `PUT` method for updates and `404 Not Found` error handling. The frontend checks the response status to display the error.

---

## 6. Student API
**Problem Statement**: Create a student registry. Features include adding a student (name and email), listing all students, and updating a student's email address.

- **Folder**: `mysql_assignments/node-mysql-api`
- **Commands**:
  ```bash
  cd mysql_assignments/node-mysql-api
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: Uses the `PATCH` or `PUT` method for partial updates. The frontend uses a `prompt()` box to quickly get the new email from the user.

---

## 7. Notes File API (Node.js File-based)
**Problem Statement**: Create a note-taking app that saves data to a local JSON file (`notes.json`) instead of a database. Implement Add, Show, and Delete functionality.

- **Folder**: `node_assignments/notes-api`
- **Commands**:
  ```bash
  cd node_assignments/notes-api
  node server.js
  ```
- **How to view**: Open `http://localhost:3000` in your browser.
- **Guidance**: This project uses the built-in `fs` (File System) module of Node.js. It's a great example of how to persist data without a database server.

---

## Troubleshooting
- **Port already in use**: If you see an error like `EADDRINUSE`, it means another server is running on port 3000. Close it before starting a new one.
- **MySQL Connection Error**: Check your MySQL username and password in the `server.js` file of the respective project.
- **CORS Issues**: Since we are serving the frontend as a static file from the same server, you shouldn't see CORS errors.

---
*Created for WDD Lab Assignments*
