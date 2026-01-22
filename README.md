# Smart-Expense-Tracker
Smart Expense Tracker is a secure full-stack web app that allows users to register, log in, and manage daily expenses. It uses REST APIs, MongoDB, and JWT authentication to ensure data security. Users can add, update, delete expenses and view visual analytics of their spending patterns.

🚀 Features

User Registration & Login
JWT-based Authentication & Authorization
Password Hashing using bcrypt
Add, Update, Delete Expenses (CRUD)
Category-wise and Monthly Expense Tracking
Interactive Charts & Analytics
Secure, User-specific Data Access

🧱 Tech Stack
Frontend
HTML
CSS
JavaScript
Chart.js
Backend
Node.js
Express.js
REST APIs
Database
MongoDB
Mongoose
Security
JSON Web Tokens (JWT)
bcrypt
Auth Middleware
CORS & Input Validation

🔐 Security Highlights
Passwords are securely hashed before storage
JWT tokens protect all private routes
Middleware ensures users can only access their own data
No sensitive data exposed on the client side

🔁 Application Flow
User registers or logs in
Backend validates credentials
JWT token is generated and sent to client
Client sends JWT with each request
Backend verifies token before database access
