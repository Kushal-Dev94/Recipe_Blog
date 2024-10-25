# Recipe Blog - Using Node.js and MongoDB

## Installation
To run this project, install it locally using npm:

```
$ npm install
$ npm start
```
Then go to: http://localhost:3000/

# Recipe Blog Project - Summary & Tech Stack Overview

## Summary  
The Recipe Blog is a full-stack web app where users can share and explore recipes. It follows the **MVC** (Model-View-Controller) pattern, using **Node.js**, **Express**, **MongoDB**, and **Mongoose** on the backend, and **EJS**, **Bootstrap**, and custom CSS on the frontend for a responsive, dynamic user experience.

---

## Backend Technologies

**Node.js**  
- **File**: `app.js`  
- **Purpose**: Executes JavaScript on the server, handling multiple requests efficiently.

---

**Express**  
- **Files**: `app.js`, `server/routes`  
- **Purpose**: Simplifies route management, efficiently handling user requests and responses.

---

**MongoDB**  
- **Files**: `app.js` (connection), `models/Recipe.js`, `models/Category.js`  
- **Purpose**: Stores recipes and categories in a secure, cloud-based NoSQL database (MongoDB Atlas).

---

**Mongoose**  
- **Files**: `models/Recipe.js`, `models/Category.js`  
- **Purpose**: Manages MongoDB data with schemas, providing structured data and simple CRUD operations.

---

## Frontend Technologies

**EJS (Embedded JavaScript)**  
- **Files**: `views/` folder (e.g., `index.ejs`, `recipe.ejs`)  
- **Purpose**: Renders dynamic HTML pages, displaying data like recipes and categories.

---

**Bootstrap**  
- **Files**: `views/layout.ejs`, `.ejs` templates  
- **Purpose**: Provides responsive design, ensuring a consistent, mobile-friendly layout.

---

**Custom Stylesheet (styles.css)**  
- **Files**: `public/styles.css`  
- **Purpose**: Adds custom styling to complement Bootstrap and align with the app’s theme.

---

## MVC Structure

**Models**  
- **Files**: `models/Recipe.js`, `models/Category.js`  
- **Purpose**: Define data structure, managing recipe and category data with validation and easy manipulation.

---

**Views**  
- **Files**: `views/` folder (e.g., `index.ejs`, `recipe.ejs`)  
- **Purpose**: Render HTML views for users, populated with real-time data from the server.

---

**Controllers (Routes)**  
- **Files**: `server/routes/recipeRoutes.js`, `server/routes/categoryRoutes.js`  
- **Purpose**: Interact with Models to fetch and manage data, passing it to Views for display.

---

