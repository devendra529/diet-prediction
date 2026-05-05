# 🥗 diet_prediction

A simple AI-based web app that helps users get diet suggestions and basic nutrition insights. This project is built for learning and hackathon purposes using modern web technologies.

---

## 🚀 Features

* 🔐 Login & Signup (File-based system, no database)
* 🧠 Basic Diet Prediction (based on user input)
* 📸 Food Image Upload (for future nutrition analysis)
* 🤖 Chat Assistant (for diet-related questions)
* 💻 Clean and responsive UI

---

## 🛠️ Tech Stack

* **Frontend:** Next.js, Tailwind CSS
* **Backend:** Node.js (API routes in Next.js)
* **Storage:** File System (No MongoDB used)
* **Authentication:** Custom Login/Signup using file storage
* **Deployment:** Vercel

---

## 📂 Project Structure

```
/app
  /login
  /signup
  /dashboard
  /predict

/lib
  auth.js

/components
  Navbar
  Form

/data
  users.json   // stores user data
```

---

## ⚙️ Getting Started (Full Setup Guide)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/diet_pridiction.git
cd diet_pridiction
```

---

### 2️⃣ Install all dependencies

Make sure you have **Node.js installed** (v18 or above recommended)

```bash
npm install
```

This will install:

* Next.js
* React
* Tailwind CSS
* All required packages automatically

---

### 3️⃣ Run the development server

```bash
npm run dev
```

---

### 4️⃣ Open in browser

Go to 👉 https://diet-pridiction.vercel.app/

---

## 🔑 How Authentication Works

* User data is stored in a local file (`users.json`)
* On signup → user details are saved
* On login → credentials are verified from file
* Simple and useful for practice projects

---

## 🌐 Deployment

This project is deployed on **Vercel** for easy hosting and fast performance.

---

## 🎯 Purpose

* Practice full-stack development
* Learn authentication without database
* Build a simple AI-based project for hackathons

---


## 👨‍💻 Author

Devendra Pratap Singh

---

## ⭐ Note

This is a beginner-friendly project. It can be improved by adding:

* Database (MongoDB / Firebase)
* Better AI models
* Secure authentication (JWT)
