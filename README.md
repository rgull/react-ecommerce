# react-ecommerce

E-Commerce Store
A full-stack e-commerce web application with role-based access control, built using React, Redux, Node.js, Express, and MongoDB. Users can browse products, add them to a cart, and admins can manage users and inventory through an admin panel.

👨‍💻 Frontend (React)
🔍 Global Product Search

📂 Category-Based Filtering

💲 Price-Based Filtering (Low to High / High to Low)

👀 Product Detail View with Image Zoom

🛒 Add to Cart with Quantity Increment/Decrement

🧑‍🤝‍🧑 Two User Roles: General & Admin

🖼️ Multi-Image Upload for Products

☁️ Cloud Image Storage with Cloudinary

🛠️ Admin Panel to:

Edit/Add Products

Manage Users & Roles

🔐 Protected Routes for authenticated access

🛠️ Backend (Node.js + Express + MongoDB)
🍃 MongoDB Atlas for cloud-based NoSQL database

🔐 JWT Authentication with cookies for session handling

🧩 Middleware for Role & Auth Check

🛡️ Password Hashing with Bcrypt

🔄 RESTful API Structure

✅ Protected Routes for both Admin and General Users

🧱 Database Design
Users

Fields: name, email, password (hashed), role

Roles: General / Admin

Relationship: Has a Cart

Products

Fields: name, description, price, category, images (multi)

Stored images using Cloudinary

Cart

Linked to User

Includes product reference, quantity

🧰 Technologies Used

Frontend	Backend	Database	Cloud	Auth & Security
React	Node.js	MongoDB Atlas	Cloudinary	JWT
Redux	Express	Mongoose		Bcrypt
React Router				Cookies