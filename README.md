# 🌍 MERN Travel & Tourism Web Application

A full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to browse, book, and review travel destinations. Admins can manage tours, users, and bookings from a secure dashboard.

## 🚀 Features

- 🧭 Browse tours with detailed information (title, description, price, location, photos)
- 🔐 User authentication and authorization (JWT based)
- 📆 Booking system for tours
- ✍️ User reviews and ratings for tours
- ⚙️ Admin dashboard for managing users, tours, and bookings
- 📱 Fully responsive frontend design using React
- 📤 Image upload for tour listings using Multer

## 🛠️ Technologies Used

### Frontend
- React.js
- Redux Toolkit
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication
- Multer (image upload)
- bcrypt (password hashing)

### Tools
- Postman (API testing)
- Git & GitHub
- VS Code

## 📁 Project Structure
📦MERN-Travel-Tourism-App
┣ 📁backend
┃ ┣ 📂controllers
┃ ┣ 📂models
┃ ┣ 📂routes
┃ ┣ 📂middleware
┃ ┗ server.js
┣ 📁frontend
┃ ┣ 📂components
┃ ┣ 📂pages
┃ ┣ 📂redux
┃ ┗ App.js / index.js


## ⚙️ Getting Started

### 1. Clone the Repository
```bash
  git clone https://github.com/YOUR-USERNAME/MERN-Travel-Tourism-App.git
  cd MERN-Travel-Tourism-App

### 2. Install the Dependencies

  ## Backend
  cd backend
  npm install
  
  ## Fronend
  cd ../frontend
  npm install

### 3. Configure Environment Variables
Create a .env file in the backend directory:

  PORT=5000
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret

### 4. Run the App

  ## Backend
  cd backend
  npm start

  ## Frontend
  cd frontend
  npm start




