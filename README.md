# 🔐 User Authentication API (Node.js + Express + MongoDB)

A secure backend API for user authentication with features like **registration**, **login**, **logout**, **JWT-based authentication**, and **password encryption** using `bcrypt.js`.

---

## 🧰 Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT (JSON Web Tokens), bcrypt.js
- **Testing Tool:** Postman

---

## ✨ Features

- ✅ User Registration
- ✅ Secure Login with JWT
- ✅ Password encryption with bcrypt
- ✅ Protected routes using JWT middleware
- ✅ Environment variable handling using `.env`

---

## 📁 Folder Structure

```
user-auth-system/
├── config/           # DB connection logic
├── controllers/      # Business logic
├── middleware/       # JWT middleware
├── models/           # Mongoose models
├── routes/           # Auth routes
├── .env.example      # Sample env variables
├── README.md
└── server.js         # Entry point
```

---

## 📦 Setup Instructions

1. **Clone the Repo**

```bash
git clone https://github.com/sgautam-02/user-auth-api.git
cd user-auth-api
```

2. **Install Dependencies**

```bash
npm install
```

3. **Configure Environment**

Rename `.env.example` to `.env` and add your values:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret_key
```

4. **Start the Server**

```bash
npm run dev
```

5. **Test APIs using Postman**

---

## 📌 Author

**Shreya Gautam**  
B.E. CSE, RNSIT | Passionate about full-stack development 🌐

