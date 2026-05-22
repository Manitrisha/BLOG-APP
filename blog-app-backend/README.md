# Blog App Backend

This is the backend part of the Blog Application built using Node.js, Express.js, and MongoDB.

## Features

- User Authentication
- Admin, Author, and User APIs
- JWT Token Authorization
- MongoDB Database Connection
- REST API Architecture
- Middleware Handling
- Environment Variable Support

---

# Project Structure

```bash
blog-app-backend/
│
├── APIs/
│   ├── adminApi.js
│   ├── authorApi.js
│   └── userApi.js
│
├── config/
│   └── db.js
│
├── middlewares/
│   └── verifyToken.js
│
├── models/
│   ├── userModel.js
│   └── articleModel.js
│
├── .gitignore
├── README.md
├── admin-req.http
├── author-req.http
├── user-req.http
├── package.json
├── package-lock.json
├── render.yaml
└── server.js
```

---

# Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- dotenv
- cors

---

# Installed Packages

```bash
npm install express mongoose dotenv cors bcryptjs jsonwebtoken
```

Development dependency:

```bash
npm install nodemon --save-dev
```

---

# Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000
DBURL=your_mongodb_connection
SECRET_KEY=your_secret_key
```

---

# Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move to backend folder:

```bash
cd blog-app-backend
```

Install dependencies:

```bash
npm install
```

Run the server:

```bash
npm start
```

For development:

```bash
npm run dev
```

---

# API Modules

## Admin APIs

- Manage users
- Manage articles
- Admin authentication

## Author APIs

- Create articles
- Update articles
- Delete articles

## User APIs

- Read articles
- User registration
- User login

---

# Middleware

## verifyToken Middleware

Used for:

- Token verification
- Route protection
- Authorization

---

# Database Configuration

MongoDB connection is handled inside:

```bash
config/db.js
```

---

# Request Files

- `admin-req.http`
- `author-req.http`
- `user-req.http`

These files are used for API testing.

---

# Deployment

Backend deployment configuration:

```bash
render.yaml
```

---

# Author

Developed as a MERN Stack Blog Application Project.
