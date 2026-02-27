# 🚀 Multi-Step Registration Wizard

A modern, professional multi-step onboarding form built using **React**, **React Hook Form**, and **Zod** with real-time validation and smooth user experience.

This project demonstrates enterprise-level form handling techniques including schema validation, controlled state management, conditional rendering, and UX best practices.

---

## 📌 Project Overview

This Registration Wizard simulates real-world onboarding flows such as:

- Bank account creation
- SaaS product signup
- Profile setup process

Instead of showing all fields on one page, the form is divided into logical steps to improve user experience.

---

## 🧠 Features

### ✅ Multi-Step Form (Wizard)
- Step 1: Personal Information
- Step 2: Account Details
- Step 3: Review & Submit

### ✅ React Hook Form
- High performance
- Minimal re-renders
- Clean form management

### ✅ Zod Schema Validation
- Type-safe validation
- Centralized validation logic
- Password match validation using `.refine()`

### ✅ Real-Time Validation
- Errors appear as the user types
- No waiting for submission

### ✅ Disabled Navigation
- "Next" button disabled until fields are valid

### ✅ Password Visibility Toggle
- Show/Hide password with icon

### ✅ Progress Bar
- Visual progress indicator (Step X of 3)

### ✅ Data Persistence Between Steps
- Form values remain intact when navigating back

### ✅ Success Screen
- Console logs final data
- Displays success message

---

## 🛠 Tech Stack

- React (Vite)
- react-hook-form
- zod
- @hookform/resolvers
- lucide-react
- CSS (Custom Styling)

---

## 📂 Folder Structure
src/
│
├── components/
│ ├── Step1.jsx
│ ├── Step2.jsx
│ ├── Step3.jsx
│ └── Success.jsx
│
├── App.jsx
├── main.jsx
└── styles.css


---

## ⚙️ Installation & Setup Guide

### 1️⃣ Clone or Create Project

```bash
npm create vite@latest registration-wizard

Select:

React

JavaScript

2️⃣ Install Dependencies
cd registration-wizard
npm install
npm install react-hook-form zod @hookform/resolvers lucide-react
3️⃣ Start Development Server
npm run dev

Open browser:

http://localhost:5173

🔍 Validation Rules
Step 1

First Name → Minimum 2 characters

Last Name → Minimum 2 characters

Date of Birth → Required

Step 2

Email → Must be valid format (contains @ and domain)

Password → Minimum 8 characters

Confirm Password → Must match Password

🧩 How It Works
State Management

The parent component (App.jsx) holds:

Current step

Combined form data

Submission status

Each step:

Uses react-hook-form

Validates using zod

Sends validated data to parent

🏗 Architecture Approach

Conditional Rendering for step switching

Schema-based validation

Centralized data storage in parent

Component separation for scalability

Enterprise form handling standard

🎯 Learning Outcomes

This project demonstrates understanding of:

Controlled Components

Form State Management

Schema Validation

Real-time UX feedback

Conditional Rendering

Multi-step form architecture

Clean UI design

Professional React practices

🚀 Possible Improvements

Convert to TypeScript

Add Framer Motion animations

Add backend integration (Node.js / Express)

Deploy on Vercel

Add dark mode toggle

Add API submission

👨‍💻 Author

Internship Week 7 Project
Multi-Step Registration Wizard
Built with ❤️ using React

📜 License

This project is created for educational and internship purposes.
