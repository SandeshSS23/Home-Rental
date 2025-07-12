# 🏡 MERN Estate – Real Estate Marketplace Web App

MERN Estate is a full-stack real estate web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It enables users to sign in, list properties, upload images, and perform advanced searches to buy, sell, or rent properties. This platform also includes secure authentication using JWT, Firebase, and Google OAuth.

---

## 🚀 Features

- 🔐 **Authentication & Authorization** using:
  - JSON Web Tokens (JWT)
  - Firebase Authentication
  - Google OAuth Sign-In
- 🏠 **Property Listing Management** – Add, update, delete, and view property listings
- 📸 **Image Uploads** using Firebase Storage
- 🔍 **Advanced Search Functionality** – Filter listings by type, location, price, and more
- 🛠️ **State Management** using Redux & Redux-Saga (if applicable)
- 🌐 **RESTful API** built with Express and MongoDB
- ⚡ **Deployed on Vercel** (Frontend) and optionally Render (Backend)

---

## 🧱 Tech Stack

### 🔹 Frontend
- React.js
- Redux (if used)
- Tailwind CSS / Bootstrap
- Firebase (for image storage and auth)

### 🔹 Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for secure APIs

---

## ⚙️ Scripts

In the root `package.json`:

---

```json
"scripts": {
  "dev": "nodemon api/index.js",
  "start": "node api/index.js",
  "build": "npm install && npm install --prefix client && npm run build --prefix client"
}
```

---

🛠️ Installation & Setup
1. Clone the repo

```
git clone https://github.com/your-username/home-rental.git
cd home-rental
```

2. Setup environment variables

Create a .env file in the root directory and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FIREBASE_API_KEY=your_firebase_api_key
```

3. Install backend dependencies

```
npm install
```

4. Install frontend dependencies

```
cd client
npm install
```

5. Run both frontend and backend

# In /client
```
npm start
```

# In root or /api
```
npm run dev
```
