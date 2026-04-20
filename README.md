# 🎬 MERN Movie Library

A full-stack Movie Library web application built using the **MERN stack (MongoDB, Express, React, Node.js)**.
Users can add, view, search, and manage movies/books with ratings and genres.

---

## 🚀 Features

* ➕ Add new movies/books
* 🔍 Search and filter by title/genre
* ⭐ Add ratings
* 🗂 Organized movie/library listing
* ⚡ Fast and responsive UI
* 🌐 Full-stack integration (Frontend + Backend + Database)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML, CSS, JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone <your-repo-url>
cd mern-movie-main
```

---

### 2️⃣ Install dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd client
npm install
```

---

### 3️⃣ Setup Environment Variables

Create a `.env` file inside `server/`:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

### 4️⃣ Run the project

#### Start backend

```bash
cd server
node index.js
```

#### Start frontend

```bash
cd client
npm start
```

---

## 🌐 API Endpoints

| Method | Endpoint | Description    |
| ------ | -------- | -------------- |
| GET    | /movies  | Get all movies |
| POST   | /movies  | Add new movie  |
| PUT    | /movies/ | Update movie   |
| DELETE | /movies/ | Delete movie   |

---

## 🎯 Future Improvements

* 🔐 User authentication (Login/Register)
* ⭐ Favorite movies feature
* 🎨 UI enhancements (Dark mode, animations)
* 📱 Mobile responsiveness
* 🌐 Deployment (Vercel + Render)

---

## 👨‍💻 Author

**Priyanshu Khamar** **Vansh Surati** **Aditya Rai**

## 💡 Note

This project is built for learning full-stack development using MERN stack and demonstrates CRUD operations, API integration, and UI design.

---
