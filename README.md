# 🌐 Social App API (Express.js + MongoDB)

Built a real-time for a social platform with Node.js, Express.js, and MongoDB. Supports user authentication, posts, comments, likes, and send and receive friend request  functionality , with clear request/response patterns and scalable service logic.

---

## 🌍 Live API

🟢 API is deployed on Vercel:  
👉 [https://social-app-eta-black.vercel.app](https://social-app-eta-black.vercel.app)

You can access it directly or test it using tools like Postman.

---

## 📮 API Documentation

📘 Full Postman Docs:  
👉 [https://documenter.getpostman.com/view/37641417/2sAYQfEUsG](https://documenter.getpostman.com/view/37641417/2sAYQfEUsG)

---

## 🧰 Tech Stack

- ⚙️ **Express.js** – Node.js web framework
- 🍃 **MongoDB + Mongoose** – Database
- 🔐 **JWT** – Authentication
- 🧪 **Postman** – API testing
- 📁 **Multer / Cloudinary** – for image upload (Optional)

---

## 📦 Features

- 📝 **User Authentication** (Register/Login)
- 👤 **Profile Update** and Info Retrieval
- ➕ **Create Post**
- ❤️ **Like / Unlike Post**
- 💬 **Add / Delete Comment**
- 🔁 **Send / receive friend request**
- 🔐 Protected Routes using JWT
- 📄 Clean RESTful structure

---
## Setup & Installation

1. **Clone the repository**  
```bash
git clone https://github.com/MohammedEsmaill/social-App.git
cd social-App

## 🔗 Sample Endpoints

```http
POST   /api/v1/auth/register       # Create new account
POST   /api/v1/auth/login          # Login and get token

GET    /api/v1/users/profile/:id   # Get user profile
PUT    /api/v1/users/profile       # Update profile
PUT    /api/v1/users/follow/:id    # Follow another user
PUT    /api/v1/users/unfollow/:id  # Unfollow user

POST   /api/v1/posts               # Create post
GET    /api/v1/posts               # Get all posts
POST   /api/v1/posts/like/:id      # Like a post
POST   /api/v1/posts/unlike/:id    # Unlike a post
POST   /api/v1/posts/comment/:id   # Comment on post
DELETE /api/v1/posts/comment/:id   # Delete comment
