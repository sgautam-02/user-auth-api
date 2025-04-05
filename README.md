# 🔐 User Authentication API

A secure user authentication system using Node.js, Express, MongoDB, bcrypt.js, and JWT.

---

## 📌 Features

- User Signup (with password hashing)
- User Login (JWT token generation)
- User Logout (client-side token removal)
- Password encryption using bcrypt.js
- Token-based session handling using JWT
- MongoDB as the database

---

## 🔧 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT, bcrypt.js

---

## 📂 Folder Structure

```
user-auth-system/
│
├── config/
│   └── db.js
├── models/
│   └── User.js
├── routes/
│   └── authRoutes.js
├── middleware/
│   └── authMiddleware.js
├── controllers/
│   └── authController.js
├── .env.example
├── server.js
├── package.json
└── README.md
```

---

## 🔐 Environment Variables

Create a `.env` file and fill in the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 🚀 How to Run

```bash
# Install dependencies
npm install

# Run the server
npm start
```

---

## 📬 API Endpoints

### 🔸 Signup

`POST /api/auth/signup`

**Request Body:**
```json
{
  "name": "Shreya Gautam",
  "email": "shreya@example.com",
  "password": "secure123"
}
```

**Response:**
```json
{
  "token": "<jwt_token>"
}
```

---

### 🔸 Login

`POST /api/auth/login`

**Request Body:**
```json
{
  "email": "shreya@example.com",
  "password": "secure123"
}
```

**Response:**
```json
{
  "token": "<jwt_token>"
}
```

---

### 🔸 Logout

`POST /api/auth/logout`

**Response:**
```json
{
  "msg": "Logout successful, remove token from client"
}
```

---

## ✅ Status

- [x] Express server setup
- [x] MongoDB connection
- [x] User signup/login/logout
- [x] Password encryption with bcrypt
- [x] JWT-based authentication
- [x] API tested with Postman
- [x] .env.example created
- [x] README complete

---

## 📁 Version Control

Project maintained on [GitHub](#)

---

## 👩‍💻 Author

**Shreya Gautam**  
Computer Science Engineering, RNSIT

