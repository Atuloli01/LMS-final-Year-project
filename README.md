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

1. Clone the repository:
   ```bash
   git clone https://github.com/Atuloli01/LMS-final-Year-project.git
   cd LMS-final-Year-project
