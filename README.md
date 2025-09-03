

# Mini Social App

A simple social media web application built with the *(MongoDB, Express, Node.js).
This project is designed as a learning project to understand backend development, authentication, and CRUD operations.

---

## 🚀 Features

* 🔐 User Authentication (Register/Login with hashed passwords & JWT)
* 👤 User Profiles
* 📝 Create, Read, Update, Delete Posts
* ❤️ Like & Comment System (basic interactions)
* 🍪 Cookie-based Authentication with JWT
* 📸 File Uploads with Multer (profile pics/posts)
* 🌐 EJS for templating

---

## 🛠️ Tech Stack

* **Frontend:** EJS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB with Mongoose
* **Authentication:** JWT + Bcrypt
* **Other Tools:** Multer, Cookie-Parser

---

## 📂 Project Structure

```
mini-social-app/
│── models/        # Mongoose models (User, Post)
│── routes/        # API routes
│── views/         # EJS templates
│── config/        # Configurations (Multer setup, etc.)
│── public/        # Static assets
│── app.js         # Main server file
│── package.json
```

---

## ⚙️ Installation & Setup

1. Clone the repo:

   ```bash
   git clone https://github.com/Sourishharh/mini-social-app.git
   cd mini-social-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory:

   ```env
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_secret_key
   PORT=3000
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. Open in browser:

   ```
   http://localhost:3000
   ```

---

## 🔮 Future Improvements

* Add React frontend (currently using EJS)
* Implement real-time chat with Socket.io
* Deploy on **Render / Vercel / Netlify** + MongoDB Atlas
* Improve UI with TailwindCSS or Material UI

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a PR.

---
