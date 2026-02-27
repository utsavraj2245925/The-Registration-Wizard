# 🧠 Internship Week 7 – Multi-Step Registration Wizard

## 📌 Project Title
Multi-Step Registration Wizard (Enterprise-Level Form Handling)

---

## 🎯 Objective

Build a professional multi-step onboarding form using modern React best practices.  
The form should collect user data across multiple steps while maintaining state, validating input in real-time, and providing a clean, user-friendly experience.

---

## 📋 Project Requirements

### 1️⃣ Multi-Step Form Structure

The form must be divided into **three separate steps**:

- **Step 1 – Personal Information**
  - First Name
  - Last Name
  - Date of Birth

- **Step 2 – Account Details**
  - Email
  - Password
  - Confirm Password

- **Step 3 – Review & Submit**
  - Display all entered data
  - Allow user to go back and edit
  - Final submission

---

### 2️⃣ Navigation

- Include **Next** and **Back** buttons
- User data must persist between steps
- Navigation should not reset previously entered data

---

### 3️⃣ State Management

- Parent component should manage:
  - Current step
  - Combined form data
  - Submission state
- Data from each step should be merged into a central state object

---

### 4️⃣ Form Handling (Industry Standard)

The form must use:

- `react-hook-form` for performance and controlled input management
- `zod` (or `yup`) for schema-based validation
- `@hookform/resolvers` for integrating schema validation

---

### 5️⃣ Real-Time Validation Rules

Validation must occur as the user types.

#### Step 1:
- First Name → Minimum 2 characters
- Last Name → Minimum 2 characters
- Date of Birth → Required

#### Step 2:
- Email → Must be valid format
- Password → Minimum 8 characters
- Confirm Password → Must match password exactly

---

### 6️⃣ Disabled Navigation Buttons

- "Next" button must remain disabled until all fields in current step are valid.

---

### 7️⃣ UX Enhancements

- Show/Hide Password toggle
- Error messages under invalid inputs
- Clean and professional layout
- Smooth progress indicator

---

### 8️⃣ Progress Bar

- Display progress indicator:
  - "Step X of 3"
  - Visual progress bar

---

### 9️⃣ Final Submission

- On final submit:
  - Log full data object to console
  - Display success screen

---

## 🏗 Architecture Approach

- Component-based design
- Conditional rendering for steps
- Centralized state in parent
- Schema-driven validation
- Clean UI with modern styling

---

## 📚 Learning Goals

This project demonstrates understanding of:

- Controlled Components
- Form State Management
- Schema Validation
- Conditional Rendering
- UX Design Principles
- Enterprise Form Architecture
- React Best Practices

---

## 🚀 Expected Outcome

A fully functional, multi-step onboarding wizard that:

- Preserves data across steps
- Validates inputs in real-time
- Prevents invalid submissions
- Provides a smooth user experience
- Follows modern enterprise-level React standards

---

## 👨‍💻 Submission Type

Frontend React Application  
Built using Vite + React Hook Form + Zod
