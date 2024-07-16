# Blog Web Application

This project is a simple blog web application built using Node.js, Express.js, and EJS (Embedded JavaScript). It allows users to create, view, edit, and delete blog posts dynamically. The application does not use a database, and posts are stored in memory during the session.

## Features
- **Create Post:** Users can create new blog posts by entering a title and content.
- **View Posts:** All created posts are displayed on the home page.
- **Edit Post:** Users can edit existing posts by clicking on the "Edit" button and updating the title or content.
- **Delete Post:** Posts can be deleted from the home page using the "Delete" button.
- **Responsive Design:** The application is styled using Bootstrap for a responsive and user-friendly experience across devices.

## Technologies Used
- **Backend:** Node.js, Express.js
- **Frontend:** EJS, Bootstrap
- **Others:** UUID for generating unique IDs for posts, Body-parser middleware for handling form data.

## Project Structure
- **index.js:** Entry point of the application where Express server is configured, routes are defined, and middleware is set up.
- **views/:** Contains EJS templates for rendering HTML pages (e.g., `home.ejs`, `edit.ejs`).
- **public/:** Includes static assets like CSS files (`styles.css`) used for styling.
