# WDD Viva Preparation Guide: Questions & Answers

This guide covers the core concepts used in your 47 assignments to help you prepare for your oral examination (viva).

---

## 1. HTML & CSS
**Q: What is the difference between Block and Inline elements?**
**A**: Block elements (like `<div>`, `<h1>`) start on a new line and take full width. Inline elements (like `<span>`, `<a>`) only take as much width as necessary and do not start on a new line.

**Q: Explain the CSS Box Model.**
**A**: Every element is a box. It consists of: **Content** (text/images), **Padding** (space inside border), **Border** (line around padding), and **Margin** (space outside border).

**Q: What is Flexbox?**
**A**: Flexbox is a CSS layout module that makes it easy to align and distribute space among items in a container, even when their size is unknown.

---

## 2. JavaScript
**Q: What is the DOM (Document Object Model)?**
**A**: The DOM is a programming interface for web documents. It represents the page as a tree of objects that JavaScript can manipulate (change text, colors, etc.).

**Q: Difference between `var`, `let`, and `const`?**
**A**: `var` is function-scoped. `let` and `const` are block-scoped. `const` cannot be reassigned, while `let` can.

**Q: What is the `fetch()` API?**
**A**: It is a modern JavaScript interface used to make network requests (like getting data from a server). It returns a Promise.

---

## 3. XML & XSD
**Q: What is the difference between Well-formed and Valid XML?**
**A**: **Well-formed** means it follows basic XML rules (tags closed, single root). **Valid** means it also follows the rules defined in a specific schema (XSD).

**Q: What is the purpose of XSD?**
**A**: XML Schema Definition (XSD) describes the structure of an XML document, including what elements are allowed and their data types (e.g., "age" must be a number).

---

## 4. React.js
**Q: What is a Component in React?**
**A**: Components are the building blocks of a React app. They are independent, reusable pieces of UI (like a Button or Header).

**Q: State vs. Props?**
**A**: **Props** (Properties) are passed from parent to child and are read-only. **State** is internal to a component and can change over time.

**Q: What is the Virtual DOM?**
**A**: It is a lightweight copy of the real DOM. React uses it to figure out exactly what changed and update only those parts, making the app faster.

**Q: Explain `useState` and `useEffect`.**
**A**: `useState` allows you to add state to functional components. `useEffect` lets you perform side effects (like fetching data) after the component renders.

---

## 5. Node.js & Express.js
**Q: What is Node.js?**
**A**: Node.js is a JavaScript runtime built on Chrome's V8 engine that allows you to run JavaScript on the server side.

**Q: What is Middleware in Express?**
**A**: Middleware functions are functions that have access to the request object (`req`), response object (`res`), and the `next` function. They can modify requests or end the response.

**Q: What are REST APIs?**
**A**: REST (Representational State Transfer) is an architectural style for designing networked applications. It uses HTTP methods: **GET** (Read), **POST** (Create), **PUT** (Update), **DELETE** (Remove).

---

## 6. MySQL & Connectivity
**Q: How do you connect Node.js to MySQL?**
**A**: We use libraries like `mysql2`. We create a connection object with host, user, password, and database details, and then call `db.connect()`.

**Q: What is a Primary Key?**
**A**: A unique identifier for each record in a table (e.g., `student_id`). It cannot be null.

---

## 7. Deployment
**Q: What is a Production Environment?**
**A**: It is the live environment where the final version of the web app is hosted (e.g., on Vercel or Heroku) so that real users can access it.

**Q: Why do we use `.env` files?**
**A**: To store sensitive information like database passwords or API keys securely, so they are not hardcoded in the source code.

---
*Good luck with your Viva!*
