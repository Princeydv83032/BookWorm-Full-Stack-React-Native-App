📚 BookWorm – Full-Stack React Native App

BookWorm is a full-stack cross-platform mobile application built with React Native (Expo) and Node.js/Express that allows users to share, browse, and rate books.
It supports Android, iOS, and Web, featuring secure authentication, image uploads, and user profile management.

🚀 Tech Stack

Frontend: React Native (Expo)
Backend: Node.js, Express.js
Database: MongoDB (Mongoose ORM)
Cloud Storage: Cloudinary
Authentication: JWT (JSON Web Token)
Deployment: Render (Backend)

💡 Features

📖 Book Sharing – Users can upload books with images, titles, authors, and ratings.

🔐 JWT Authentication – Secure login, signup, and protected routes.

🧩 CRUD Operations – Add, edit, delete, and view books in real time.

☁️ Cloudinary Integration – Store and serve book cover images efficiently.

🎨 Dynamic Themes – Switch between multiple UI themes.

🔁 Infinite Scrolling – Smooth, continuous content loading experience.

👤 Profile Management – Update personal details and view user activity.

🌐 Cross-Platform Ready – Works on Android, iOS, and web using Expo.

## 📁 .env Setup

### ⚙️ Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=<YOUR_MONGO_DB_URI>
JWT_SECRET=<JWT_SECRET>

CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>

API_URL=<YOUR_DEPLOYED_API_URL>
```

## ⚙️ Run the backend

```bash
cd backend
npm install
npm run dev

```

## 📱 Run the mobile

```bash
cd mobile
npm install
npx expo
```
