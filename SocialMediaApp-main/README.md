# FullStack Social Media App

Build a COMPLETE Fullstack Responsive MERN App with Auth, Likes, Dark Mode | React, MongoDB, MUI

Client will be running on PORT 3000
Server will be running on PORT 3001

Client - React JS
Server - Spring Boot
Database - MongoDB

Frontend
React Router - for navigation
Formik and Yup - for form and form validation
Redux toolkit - for state management
Redux Persistent - for local storage
React Drop zone - for image upload

Backend
Node.js - runtime
Express.js - backend framework
Mongoose - for managing MongoDB
JWT - authentication
Multer - file upload

Node.js is built using chrome's V8 javascript engine. So, it can be run on our laptops without any issue.

libraries used:
Nodemon - is a live server. So, it refreshes everytime we save.
bcrypt - password encryption
gridfs-stream - file upload
multer, multer-gridfs-storage - upload files locally
helmet - request safety
morgan - logging
jsonwebtoken - authentication
mongoose - for mongodb access

Creating package.json file: npm init -y -> -y is used to put default values in the configuration

Note: To use, import statements instead of require statements, we need to add "type": "module" in package.json file. And you need to add these middle ware too:
const filename = fileURLToPath (import.meta.url);
const dirname = path. dirname(filename);

Deployed the app on render.com
Follow this video for the deployment-
https://www.youtube.com/watch?v=MTPb4smwpU8

Deployed frontend and backend seperately
In the API calls, we used the link where backend was deployed.
