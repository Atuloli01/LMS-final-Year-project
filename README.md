# 📚 E-Learning & Sharing Management System (ELMS-AI)

> A modern web-based learning platform blending academics with social interactivity — like Instagram but smarter 📸 + 📖.

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Production-green)
![Made with ❤️](https://img.shields.io/badge/Made%20with-Love-ff69b4)

---

## 🚀 Overview

ELMS-AI is a full-stack Learning Management System for students and instructors with features like:

- 📹 Video lectures & PDF resources
- 📝 Quizzes, Assignments, and Feedback
- 📊 Performance tracking dashboards
- 🔒 OTP-secured login and role-based access
- 💬 Social features (soon!)

This is education, upgraded. Tailored for small to medium institutions and independent educators.

---

## 🧠 Motivation

After the pandemic, remote learning became a **necessity**, not an option. ELMS-AI is built to address:

- Accessibility from anywhere 🌍
- Secure, engaging experiences 🔐
- Blended learning with social interactivity 💡

---

## 🎯 Objectives

- Dual-role access: `Student` & `Instructor`
- Course & content management
- Assessment & grading modules
- Scalable, intuitive interface
- Analytics & performance tracking

---

## 🧰 Tech Stack

| Layer         | Tech                          |
|---------------|-------------------------------|
| 🌐 Frontend   | React.js, Tailwind CSS, HTML, CSS, JavaScript |
| ⚙️ Backend    | PHP (primary), Node.js, Express.js, Python (Django) |
| 💾 Database   | MySQL (Relational), MongoDB (NoSQL optional) |
| 🔐 Auth       | OTP Verification, JWT Tokens  |
| 🧠 State Mgmt | Redux / Context API           |

---

## 🧪 Features

### 🔐 Authentication & Roles
- OTP-based login and secure password reset
- JWT token handling
- Role-based authorization (`Admin`, `Student`, `Instructor`)

### 🧑‍🏫 Instructor Portal
- Create & manage courses
- Upload lectures, PDFs, assignments
- Assess submissions and grade

### 👨‍🎓 Student Portal
- Enroll in courses
- View materials, submit work
- Track progress & get feedback

### 📊 Analytics & Reporting
- Course completion stats
- Student performance graphs
- Admin dashboard for platform insights

### 🛠 Extras
- Modular course structure
- Discussion forums (upcoming)
- Real-time notifications
- Certificate generation on course completion

---

## 🏗️ System Design

- **Architecture**: Traditional 3-tier (Frontend, Backend, DB)
- **SDLC Model**: Waterfall (perfect for well-scoped academic projects)
- **Diagrams**: ER Model, DFDs (Level 0 and 1), Sequence & Activity Diagrams

---

## 🧾 Database Schema

**Main Tables (SQL)**

- `users`: ID, name, email, password, role
- `courses`: ID, title, instructor_id
- `enrollments`: course_id, user_id, progress
- `videos`, `notes`, `assignments`, `results`, `feedback`

MongoDB used optionally for scalability in analytics, dynamic content.

---

## 🛠️ Local Setup Guide

### 💾 Requirements

- OS: Windows 7/10 or macOS/Linux
- Tools: XAMPP or WAMP for PHP + MySQL
- Node.js (for advanced backend optional features)
- Browser: Chrome / Firefox

### 🔧 Installation Steps

#### ✅ Using PHP (XAMPP)

```bash
# Clone the repository
git clone https://github.com/Atuloli01/LMS-final-Year-project.git

# Move into the project directory
cd LMS-final-Year-project

# Add a .env file with necessary keys
# (You can use a text editor like nano or VS Code to create it)

# Open two terminal tabs and run the following in each:

# In the first terminal
cd client/
npm run dev

# In the second terminal
cd server/
npm run dev
```

<h1>Enjoy the Project : </h1>
-----
------
<h2>Documentation: </h2>
# 🎓 MERN Stack Learning Management System (LMS)

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
![Issues](https://img.shields.io/github/issues/Atuloli01/LMS-final-Year-project)
![Forks](https://img.shields.io/github/forks/Atuloli01/LMS-final-Year-project)
![Stars](https://img.shields.io/github/stars/Atuloli01/LMS-final-Year-project)

A complete Learning Management System built using the MERN stack for seamless course management, student-teacher interaction, and secure content delivery.

---

## 📚 Table of Contents

- [🌐 Live Demo](#-live-demo)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Folder Structure](#-folder-structure)
- [⚙️ Getting Started](#️-getting-started)
- [🔐 Authentication](#-authentication)
- [📦 API Overview](#-api-overview)
- [🖼️ Screenshots](#️-screenshots)
- [🧩 Planned Features](#-planned-features)
- [🤝 Contributing](#-contributing)
- [👨‍💻 Author](#-author)
- [📄 License](#-license)
- [💬 Feedback](#-feedback)

---

## 🌐 Live Demo

> 🚀 **Coming Soon**

---

## ✨ Features

<details>
<summary>🔍 Click to Expand</summary>

### 👨‍🏫 Instructor Features
- Course creation
- Assignment uploading
- Resource management

### 🎓 Student Features
- Enrollment in courses
- Submit assignments
- View/download learning materials

### 🔒 Security & UX
- JWT authentication
- Role-based access
- Responsive UI with modern design
- Real-time chat and notifications
</details>

---

## 🛠️ Tech Stack

| Type       | Technologies                                   |
|------------|------------------------------------------------|
| Frontend   | React.js, Tailwind CSS, Axios                  |
| Backend    | Node.js, Express.js                            |
| Database   | MongoDB, Mongoose                              |
| Auth       | JWT, bcrypt                                    |
| Realtime   | Socket.io                                      |
| Storage    | Cloudinary                                     |
| Dev Tools  | Concurrently, Nodemon, ESLint                  |

---

## 📁 Folder Structure

```plaintext
LMS-final-Year-project/
├── client/                 # Frontend (React)
│   ├── public/
│   └── src/
│       ├── components/     # Reusable components
│       ├── pages/          # Route-based components
│       ├── context/        # Auth/context providers
│       └── utils/          # Axios, validators, etc.
│
├── server/                 # Backend (Node + Express)
│   ├── controllers/        # Logic for routes
│   ├── routes/             # API endpoints
│   ├── models/             # Mongoose schemas
│   ├── middleware/         # Auth middleware
│   └── config/             # DB connection & config
│
├── .env                    # Environment config (not committed)
├── package.json            # Root config for scripts
├── README.md               # You’re here
```

⚙️ Getting Started
1️⃣ Clone the Repository
``` bash
git clone https://github.com/Atuloli01/LMS-final-Year-project.git
cd LMS-final-Year-project
```
<div>2️⃣ Setup Environment Variables
Create a .env file in server/ with:  </div>
``` bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
```
3️⃣ Install Dependencies
``` bash


# Frontend
```
# Backend
cd server
npm install

cd client
npm install
4️⃣ Run the App
Use 2 terminals:

# Terminal 1
cd server
npm run dev

# Terminal 2
cd client
npm run dev
```
🔐 Authentication
JWT Token-based login/register

Passwords hashed via bcrypt

Role-based control (Admin, Instructor, Student)

Protected routes using middleware

📦 API Overview
RESTful APIs for:

User registration & login

Course and module management

Assignment uploads

Chat & messaging

File access via Cloudinary

Add Postman docs soon.

🖼️ Screenshots
(Add screenshots of your UI below)
📷 Course dashboard
📷 Instructor panel
📷 Student assignment view

🧩 Planned Features
 Instructor dashboard

 File uploads (video, docs)

 Notifications & Announcements

 Stripe / Razorpay integration

 Mobile-friendly PWA support

🤝 Contributing
bash
Copy
Edit
# 1. Fork this repo
# 2. Create a new branch
git checkout -b feature/your-feature

# 3. Make your changes
# 4. Push to GitHub
git push origin feature/your-feature

# 5. Create a Pull Request
👨‍💻 Author
Atuloli01
🔗 GitHub: Atuloli01

📄 License
This project is licensed under the MIT License.

💬 Feedback
Have suggestions or bugs?
Please open an issue or contact me directly.


