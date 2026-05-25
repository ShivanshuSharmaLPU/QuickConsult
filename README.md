# 🏥 QuickConsult — Smart Medical Consultation Scheduler

> A smart full-stack web application designed to connect patients and doctors through a seamless appointment booking platform with secure authentication, real-time availability, and role-based access control.

---

## 🔍 Overview

**QuickConsult** simplifies the process of scheduling doctor appointments by providing:

- 🧑‍💻 A user-friendly interface for patients to search doctors and book appointments
- 👨‍⚕️ A doctor dashboard to manage schedules and appointments
- 🛠 An admin panel to manage doctors and users
- 🔐 Secure authentication and authorization

---

## ✨ Key Features

### 👨‍⚕️ Doctor Management
- Admin can add, update, and remove doctor profiles
- Doctors can manage their own availability and appointments

### 📅 Smart Appointment Booking
- Patients can view available time slots
- Book appointments with preferred doctors in seconds

### 🔐 Role-Based Access Control

| Role | Permissions |
|------|-------------|
| **Admin** | Manage doctors, users, and platform activity |
| **Doctor** | Manage availability and view appointments |
| **Patient** | Book, view, and manage consultations |

### 🔑 Secure Authentication
- JWT-based secure login
- Passwords encrypted using **Bcrypt with Salt**

### 💳 Payment Integration
- Online appointment payments via **Razorpay**

### 📜 Consultation History
- View past consultations and upcoming appointments from a single dashboard

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React.js, Axios, Tailwind CSS |
| **Backend** | Node.js, Express.js, REST API |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, Bcrypt |
| **Payment** | Razorpay |

---

## 📂 Project Structure

```
QuickConsult/
│
├── client/                     # Patient frontend (React)
│   ├── components/
│   ├── pages/
│   ├── context/
│   └── services/
│
├── admin/                      # Admin dashboard (React)
│   ├── components/
│   ├── pages/
│   └── services/
│
├── server/                     # Backend API (Node.js)
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── config/
│
└── database/
    ├── users
    ├── doctors
    ├── appointments
    └── payments
```

---

## 📌 Use Cases

### 👤 Patients
- Search doctors by specialization
- Book appointments with available slots
- View full consultation history

### 👨‍⚕️ Doctors
- Manage appointment schedules
- View and respond to patient bookings

### 🛠 Admin
- Add, edit, and remove doctors
- Manage user accounts
- Monitor overall platform activity

---

## 🔒 Security

- 🔑 Passwords hashed using **Bcrypt with Salt**
- 🛡 Authentication handled via **JWT tokens**
- 🚧 Protected routes ensure only authorized users access sensitive operations

---

## 🚀 Future Improvements

- 🔔 Real-time notifications using **WebSockets**
- 📧 Automated **Email / SMS reminders** for appointments
- 🤖 **ML-based doctor recommendation system**
- 📊 **Advanced analytics dashboard** for admin
- 🎥 **Telemedicine support** for online video consultations
- 💊 **Integrated medical store** for ordering prescribed medicines

---

## 📄 License

MIT License — free to use and modify.

---

## 👨‍💻 Author

Made with ❤️ by **Shivanshu Sharma**
