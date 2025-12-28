# 🏥 DocSpot – Seamless Appointment Booking for Health

DocSpot is a MERN Stack–based healthcare appointment booking system that simplifies the process of booking doctor appointments online. It provides a smooth experience for patients to schedule appointments and for administrators to manage doctors, time slots, and bookings efficiently.

---

## 📖 Project Description

In today’s fast-paced world, booking hospital appointments manually can be time-consuming and inefficient. DocSpot solves this problem by providing an online platform where patients can easily find doctors, select available slots, and book appointments. The system is built using the MERN stack to ensure scalability, performance, and a responsive user interface.

---

## 🚀 Features

### 👤 Patient Features
- User registration and login
- Secure authentication using JWT
- Search doctors by specialization
- Book doctor appointments online
- View appointment history
- Responsive UI for all devices

### 🧑‍⚕️ Admin Features
- Admin login
- Add, update, and delete doctors
- Manage doctor availability and time slots
- View all patient appointments
- Dashboard for appointment monitoring

---

## 🛠️ Technology Stack (MERN)

### Frontend
- React.js
- HTML5
- CSS3
- Bootstrap
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB (MongoDB Atlas / Local MongoDB)

### Authentication
- JSON Web Tokens (JWT)

---

## 📂 Project Structure

DocSpot-Seamless-Appointment-Booking-for-Health/
│
├── client/ # React Frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ └── App.js
│ ├── public/
│ └── package.json
│
├── server/ # Node + Express Backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── config/
│ ├── server.js
│ └── package.json
│
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/DocSpot-Seamless-Appointment-Booking-for-Health.git
cd DocSpot-Seamless-Appointment-Booking-for-Health

### 2️⃣ Backend Setup
cd server
npm install
server/.env:
PORT=5000
MONGO_URI=your_mongodb_docspot
JWT_SECRET=docspot123

###3️⃣ Frontend Setup

cd client
npm install
npm start
 ## ▶️ How to Run the Application
Frontend URL:  http://localhost:3000
Backend API URL: http://localhost:5000
