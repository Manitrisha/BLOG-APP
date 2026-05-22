# Blog App Frontend

This is the frontend part of the Blog Application built using React.js and Vite.

## Features

- Responsive UI
- User Authentication Pages
- Admin Dashboard
- Author Dashboard
- Blog Listing
- Article Details Page
- API Integration
- React Routing

---

# Project Structure

```bash
blog-app-frontend/
│
├── public/
│
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── App.jsx
│   └── main.jsx
│
├── .env
├── .gitignore
├── README.md
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vercel.json
└── vite.config.js
```

---

# Technologies Used

- React.js
- Vite
- React Router DOM
- Axios
- Redux Toolkit
- Bootstrap / CSS

---

# Installed Packages

```bash
npm install react-router-dom axios react-redux @reduxjs/toolkit
```

For Vite:

```bash
npm create vite@latest
```

---

# Environment Variables

Create a `.env` file inside frontend folder.

```env
VITE_API_URL=http://localhost:5000
```

---

# Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move to frontend folder:

```bash
cd blog-app-frontend
```

Install dependencies:

```bash
npm install
```

Run the frontend:

```bash
npm run dev
```

---

# Main Functionalities

## User Module

- Register
- Login
- Read blogs

## Author Module

- Add blogs
- Edit blogs
- Delete blogs

## Admin Module

- Manage users
- Manage blogs

---

# Routing

React Router is used for navigation between pages.

Example routes:

```jsx
<Route path="/" element={<Home />} />
<Route path="/login" element={<Login />} />
<Route path="/register" element={<Register />} />
```

---

# Deployment

Frontend deployment configuration:

```bash
vercel.json
```

---

# Build Command

```bash
npm run build
```

---

# Preview Build

```bash
npm run preview
```

---

# Author

Developed as a MERN Stack Blog Application Project.
