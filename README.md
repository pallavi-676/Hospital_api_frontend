# 🏥 CareNexus — Hospital Management System

A modern Hospital Management System built with **React, Vite, Axios, Node.js, Express, MongoDB, and Passport.js**.

CareNexus provides a simple interface for managing hospitals, authentication, hospital availability, and hospital records through a frontend connected to a RESTful backend API.

## 🌐 Live Application

**Frontend:**  
https://hospital-api-frontend.vercel.app/

**Backend API:**  
https://hospital-api-xk7v.onrender.com/

---

## ✨ Features

### 🔐 Authentication
- User registration
- User login
- Session-based authentication
- Passport.js authentication
- Secure password hashing with bcrypt
- User logout

### 🏥 Hospital Management
- View all hospitals
- View available hospitals
- View individual hospital details
- Add a new hospital
- Update hospital information
- Delete a hospital
- Track total and available beds

### 📊 Dashboard
- Total hospitals
- Total beds
- Available beds
- Occupancy information
- Hospital overview

### 🎨 Frontend
- Responsive React interface
- Modern healthcare-inspired design
- Clean and simple dashboard
- Responsive layout for desktop, tablet, and mobile
- Loading and error states
- Form validation

---

## 🛠️ Technologies Used

### Frontend

- React.js
- Vite
- React Router
- Axios
- Tailwind CSS
- Lucide React

### Backend

- Node.js
- Express.js
- Passport.js
- Express Session
- bcrypt.js
- CORS

### Database

- MongoDB
- Mongoose
- MongoDB Atlas
- MongoDB Compass

### Deployment

- Vercel — Frontend
- Render — Backend
- MongoDB Atlas — Database

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │   React Frontend    │
                    │       Vercel        │
                    └──────────┬──────────┘
                               │
                               │ REST API
                               ▼
                    ┌─────────────────────┐
                    │   Express Backend   │
                    │       Render        │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    │                     │
                    ▼                     ▼
              ┌───────────┐       ┌──────────────┐
              │ Passport  │       │   Mongoose   │
              │   Auth    │       │              │
              └───────────┘       └──────┬───────┘
                                         │
                                         ▼
                                  ┌─────────────┐
                                  │   MongoDB   │
                                  │    Atlas    │
                                  └─────────────┘


```

