# Smart-Expense-Tracker
Smart Expense Tracker is a secure full-stack web app that allows users to register, log in, and manage daily expenses. It uses REST APIs, MongoDB, and JWT authentication to ensure data security. Users can add, update, delete expenses and view visual analytics of their spending patterns.

🚀 Features

1. User Registration & Login
2. JWT-based Authentication & Authorization
3. Password Hashing using bcrypt
4. Add, Update, Delete Expenses (CRUD)
5. Category-wise and Monthly Expense Tracking
6. Interactive Charts & Analytics
7. Secure, User-specific Data Access


🧱 Tech Stack
Frontend
1. HTML
2. CSS
3. JavaScript
4. Chart.js

Backend
1. Node.js
2. Express.js
3. REST APIs
4. 
Database
1. MongoDB
2. Mongoose

Security
1. JSON Web Tokens (JWT)
2. bcrypt
3. Auth Middleware
4. CORS & Input Validation


🔐 Security Highlights
1. Passwords are securely hashed before storage
2. JWT tokens protect all private routes
3. Middleware ensures users can only access their own data
4. No sensitive data exposed on the client side


🔁 Application Flow
1. User registers or logs in
2. Backend validates credentials
3. JWT token is generated and sent to client
4. Client sends JWT with each request
5. Backend verifies token before database access
