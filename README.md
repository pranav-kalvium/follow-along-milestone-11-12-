# Ecommerce-Follow-Along


Welcome to the *Ecommerce Application* project!  The application demonstrates modern development practices and hands-on experience with real-world concepts.

---

## *Project Overview*

This application is built using the *MERN Stack*, a popular technology stack for building full-stack web applications.

### *Key Features*
1. *User Authentication*:
   - Users can sign up and log in using their personal credentials.
2. *Product Management*:
   - Add, update, and retrieve product data.
3. *Order Handling*:
   - Manage customer orders efficiently.
4. *Database Integration*:
   - Uses *MongoDB* to store data in a flexible and scalable manner.
   - Each API endpoint interacts with the database and serves data in a structured format (typically JSON).

---

## *Milestone 1: Project Overview*

### *MERN Stack Overview*
- The MERN stack is favored for its *JavaScript-only approach*, enabling developers to work with a single language across the application:
  - *MongoDB*: For data storage.
  - *Express.js*: To build the backend server.
  - *React.js*: To create the frontend user interface.
  - *Node.js*: For running the server-side JavaScript.



### *REST API*
- A *REST API* is used to establish communication between the client (frontend) and the server (backend). This enables:
  - *User Authentication*: Secure registration and login.
  - *Product Management*: Handling product-related operations.
  - *Order Handling*: Managing and retrieving customer orders.

---

## *Milestone 2: Project Setup*
In this milestone, we created a login page using react and tailwind css. Then we linked it to the app.jsx using a loginPage.jsx in the pages folder.
Here, we learned about the differences between css and tailwind css and how to use it effectively.

## *Milestone 3: Project Setup*
### Features Implemented
- Structured backend folders for routes, controllers, models, and middlewares.
- Set up a Node.js server using Express.
- Connected the server to MongoDB.
- Implemented basic error handling for better debugging.

## *Milestone 4: User Management and File Uploads*
### Features Implemented
- Created a User Model:
Defined a schema for storing user data using MongoDB. The schema includes fields like name, email, and password to map the structure of user information.
- Developed a User Controller:
Implemented logic for managing user-related actions such as adding new users and retrieving their information. This controller acts as a bridge between the user interface and the database.
- Set Up File Uploads with Multer:
Configured Multer to handle file uploads, allowing users to upload profile pictures or other files. Files are stored securely in the backend with paths linked to user profiles.

## *Milestone 5: User Sign-Up Page and Form Validation*
## Features Implemented
- Created the Sign-Up page :
Designed a user-friendly, clean, and simple form where users can input their details, including name, email, and password.
Added Form Validation:
- Implemented validation for user inputs such as checking if the email format is correct and ensuring the password meets certain security criteria (e.g., minimum length).
Ensured that only valid data is submitted to the server.

## *Milestone 6: Secure Password Storage and Data Handling*
## Features Implemented
- Password Encryption:
Used bcrypt to hash passwords during the signup process.
Stored only hashed passwords in the database to ensure that sensitive information is never saved as plain text.
- Secure Data Handling:
Saved user data such as name, email, and hashed password in the MongoDB database.
Ensured compliance with security standards to protect user privacy and prevent data breaches.

## *Milestone 7: Login Endpoint and Password Validation*
## Features Implemented
- Login Endpoint:
Created an endpoint to accept user credentials (email/username and password).
Retrieved the corresponding user from the database using the provided email/username.
- Password Validation:
Used bcrypt to hash the entered password during login.
Compared the hashed password with the stored hashed password in the database for authentication, ensuring that only valid users can log in.

## *Milestone 8: Product Card Component and Homepage Layout*
## Features Implemented
- Card Component:
Designed a reusable card component to display product details like name, image, and price using props.
Ensured the component is flexible and can be used for displaying multiple products on the homepage.
- Homepage Layout:
Set up a clean, responsive layout using CSS grid or flexbox for displaying the product cards in an organized manner.
Created a neat and visually appealing display for products, ensuring good user experience across different screen sizes.

## *Milestone 9: Product Creation Form*
## Features Implemented
- Product Form: A form to input product details like name, description, price, and category.
- Multiple Image Upload: Functionality to upload multiple product images.

## *Milestone 10: Product Schema and Endpoint Creation*

## Features Implemented
- *Product Schema*: Defined the structure of product data (e.g., name, description, price, image URL) using Mongoose. Ensured each field has proper validation (e.g., required fields, correct data types).
- *Endpoint Creation*: Built a POST endpoint to receive product data. Validated and saved the product details to MongoDB.

## Why Validation?
- Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.

## *Milestone 11: Fetch and Display Products*
## Features Implemented
- Endpoint to Fetch Products:
Wrote an endpoint that sends all product data to the frontend.
- Fetch Products in Frontend:
Implemented a function in the frontend to fetch all product data from the backend.
- Display Products:
Displayed the fetched product data dynamically by passing it to the product card component.

## *Milestone 12: Product Update and Delete*
## Features Implemented
- Update Product:
Implemented functionality to update existing product details. Created an endpoint to handle product updates and a form in the frontend to submit updated product data.
- Delete Product:
Implemented functionality to delete a product. Created an endpoint to handle product deletion and added a delete button in the frontend to remove products.

## *Milestone 13: Product Edit Functionality*
## Features Implemented
- Update Endpoint:
Wrote an endpoint that receives new data and updates the existing data inside MongoDB.
- Edit Button:
Added an edit button to the product card in the frontend.
- Auto-fill Form:
When the edit button is clicked, the form is auto-filled with the existing product data, allowing the user to edit and save the changes.

## *Milestone 14: Product Delete Functionality*
## Features Implemented
- Delete Endpoint:
Wrote an endpoint that deletes the product data from MongoDB using the product ID.
- Delete Button:
Added a delete button to the product card in the frontend.
- Delete Operation:
When the delete button is clicked, the product ID is sent to the server endpoint to delete the product.
