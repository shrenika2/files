# Complete Web Design and Development Lab Manual

This document contains the problem statements, folder locations, and execution instructions for all 47 assignments in the WDD Laboratory course.

---

## Part 1: HTML & CSS Basics
**Location**: `html_css_assignments/`

### 1. Profile Card (PS01)
- **Problem**: Create a personal profile card using HTML and CSS with an image, name, bio, and social media links.
- **Run**: Open `ps01_profile_card/index.html` in your browser.

### 2. Navigation Bar (PS02)
- **Problem**: Design a responsive navigation bar with a logo and menu items that change color on hover.
- **Run**: Open `ps02_nav_bar/index.html` in your browser.

### 3. Blog Layout (PS03)
- **Problem**: Create a multi-column blog layout with a header, sidebar, main content area, and footer.
- **Run**: Open `ps03_blog_layout/index.html` in your browser.

### 4. Registration Form (PS04)
- **Problem**: Build a styled registration form with input fields for name, email, password, and a submit button.
- **Run**: Open `ps04_registration_form/index.html` in your browser.

### 5. Image Gallery (PS05)
- **Problem**: Create a responsive grid-based image gallery using CSS Flexbox or Grid.
- **Run**: Open `ps05_image_gallery/index.html` in your browser.

---

## Part 2: JavaScript Fundamentals
**Location**: `javascript_assignments/`

### 6. Quiz App (PS06)
- **Problem**: A simple quiz application where users select answers and see their score at the end.
- **Run**: Open `ps06_quiz_app/index.html` in your browser.

### 7. Character Counter (PS07)
- **Problem**: Real-time character and word counter for a textarea input.
- **Run**: Open `ps07_char_counter/index.html` in your browser.

### 8. Simple Calculator (PS08)
- **Problem**: A basic calculator for addition, subtraction, multiplication, and division.
- **Run**: Open `ps08_calculator/index.html` in your browser.

### 9. Todo List (PS09)
- **Problem**: A task manager where users can add, mark as done, and delete tasks.
- **Run**: Open `ps09_todo_list/index.html` in your browser.

### 10. Countdown Timer (PS10)
- **Problem**: A timer that counts down from a user-specified number of seconds.
- **Run**: Open `ps10_countdown_timer/index.html` in your browser.

---

## Part 3: XML & XSD Validation
**Location**: `xml_xsd_assignments/`

### 11. Library Catalog (PS11)
- **Problem**: XML structure for books and an XSD to validate author, title, and year.
- **Run**: Open `ps11_library_catalog/library.xml`.

### 12. Shop Inventory (PS12)
- **Problem**: XML for products with XSD validation for price and stock levels.
- **Run**: Open `ps12_shop_inventory/inventory.xml`.

### 13. Hospital Patient (PS13)
- **Problem**: Patient records in XML with XSD validation for age and contact details.
- **Run**: Open `ps13_hospital_patient/patients.xml`.

### 14. Exam Results (PS14)
- **Problem**: XML data for student marks with XSD validation for grades.
- **Run**: Open `ps14_exam_results/results.xml`.

### 15. Flight Schedule (PS15)
- **Problem**: Flight details (source, destination, time) in XML with XSD schema.
- **Run**: Open `ps15_flight_schedule/flights.xml`.

---

## Part 4: React.js (Component & State)
**Location**: `react_assignments/`

### 16. Triple Counter (PS16)
- **Problem**: Three independent counters on one page using React state.
- **Run**: `cd react_assignments/triple-counter` -> `npm start`.

### 17. Theme Switcher (PS17)
- **Problem**: Toggle between Dark and Light mode using React context or state.
- **Run**: `cd react_assignments/theme-switcher` -> `npm start`.

### 18. Multi-step Form (PS18)
- **Problem**: A form divided into multiple steps (Personal -> Contact -> Review).
- **Run**: `cd react_assignments/multi-step-form` -> `npm start`.

### 19. Shopping Cart (PS19)
- **Problem**: Add products to a cart and calculate the total price in real-time.
- **Run**: `cd react_assignments/shopping-cart` -> `npm start`.

### 20. Expense Tracker (PS20)
- **Problem**: Track income and expenses with a balance display.
- **Run**: `cd react_assignments/expense-tracker` -> `npm start`.

*(Note: Assignments 21-25 follow similar patterns for StopWatch, Color Palette, Image Carousel, Weather Card, and Student Search).*

---

## Part 5: Node.js (File System & Modules)
**Location**: `node_assignments/`

### 26. Student Marks Processor
- **Problem**: Read a JSON file of students, calculate average, and save to a new file.
- **Run**: `node student-marks-processor/index.js`.

### 27. CLI File Tool
- **Problem**: Command line tool to create, read, and delete files using the `fs` module.
- **Run**: `node cli-file-tool/index.js [command] [filename]`.

### 28. Raw HTTP Server
- **Problem**: Create a server using the `http` module without any framework.
- **Run**: `node raw-http-server/server.js`.

---

## Part 6: Express.js (Routes & Middleware)
**Location**: `express_assignments/`

### 31. Basic Express Server
- **Problem**: Setup routes for `/`, `/status`, and `/info` with a frontend UI.
- **Run**: `node basic-express-server/server.js`.

### 32. Books REST API
- **Problem**: CRUD operations for a books collection using Express.
- **Run**: `node books-rest-api/server.js`.

### 33. Middleware Demo
- **Problem**: Implement custom logging and authentication middleware in Express.
- **Run**: `node middleware-demo/server.js`.

---

## Part 7: Full Stack (MySQL & Deployment)
**Location**: `backend_mysql_assignments/` & `mysql_assignments/`

### 41. Student Management (MySQL)
- **Problem**: Store student details in a MySQL database with a web frontend.
- **Run**: `node mysql_assignments/node-mysql-api/server.js`.

### 42. Notes/Contacts/Products APIs
- **Problem**: Dedicated full-stack apps for Notes, Contacts, and Products using MySQL.
- **Run**: `node backend_mysql_assignments/[folder]/server.js`.

### 47. Deployment (Production)
- **Problem**: Deploy an Express app to a production environment (like Vercel/Render).
- **Location**: `deployment_assignments/`

---
*End of Manual*
