🏥 Smart Medical Consultation Scheduler

A smart full-stack web application designed to manage medical consultations efficiently.
The system connects patients and doctors through a seamless appointment booking platform with secure authentication, real-time availability, and role-based access control.

🔍 Overview

The Smart Medical Consultation Scheduler simplifies the process of scheduling doctor appointments.

The platform provides:

A user-friendly interface for patients to search doctors and book appointments
A doctor dashboard to manage schedules and appointments
An admin panel to manage doctors and users
Secure authentication and authorization
✨ Key Features
👨‍⚕️ Doctor Management
Admin can add, update, and remove doctor profiles
Doctors can manage their availability and appointments
📅 Smart Appointment Booking
Patients can view available time slots
Book appointments with doctors easily
🔐 Role-Based Access

Different roles have different permissions:

Admin – manages doctors and users
Doctor – manages availability and appointments
Patient – books and manages consultations

🔑 Secure Authentication
Secure login using JWT authentication
Passwords are encrypted using Bcrypt with Salt
💳 Payment Integration
Online appointment payments using:
Razorpay

📜 Consultation History
Patients can view:
Past consultations
Upcoming appointments
🛠 Tech Stack
Frontend
React.js
Axios
Tailwind CSS / Bootstrap
Backend
Node.js
Express.js
REST API
Database
MongoDB
Mongoose
Authentication
JWT (JSON Web Token)
Bcrypt (Password hashing)
Payment Gateway
Razorpay

📂 Project Structure
```
Smart-Medical-Consultation-Scheduler
│
├── client                     # Patient frontend (React)
│   ├── components
│   ├── pages
│   ├── context
│   └── services
│
├── admin                      # Admin dashboard
│   ├── components
│   ├── pages
│   └── services
│
├── server                     # Backend API
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── middleware
│   └── config
│
└── database
    ├── users
    ├── doctors
    ├── appointments
    └── payments
```
## 📌 Use Cases

### 👤 Patients
- Search doctors by specialization
- Book appointments
- View consultation history

### 👨‍⚕️ Doctors
- Manage appointment schedules
- View patient bookings

### 🛠 Admin
- Manage doctors
- Manage users
- Monitor platform activity


## 🔒 Security

- Passwords are hashed using **Bcrypt with Salt**
- Authentication handled using **JWT tokens**
- Protected routes ensure only authorized users access sensitive operations


## 🚀 Future Improvements

- 🔔 Real-time notifications using **WebSockets**
- 📧 Automated **Email/SMS reminders** for appointments
- 🤖 **Machine Learning–based doctor recommendation system**
- 📊 **Advanced analytics dashboard** for admin
- 🎥 **Telemedicine support** for online video consultations
- 💊 **Integrated medical store** for ordering prescribed medicines
