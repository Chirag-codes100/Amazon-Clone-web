# 🛒 Amazon Clone (E-Commerce Web App)

A modern Amazon-inspired e-commerce web application built using React and Supabase.
This project demonstrates a full shopping workflow including product browsing, cart management, and order placement.

---

## 🚀 Live Demo

👉 (https://amazon-clone-web-neon.vercel.app/)

---

## 🧠 Tech Stack

### 💻 Frontend

* React.js (Vite)
* Tailwind CSS
* React Router DOM

### ☁️ Backend / Database

* Supabase (PostgreSQL + REST API)
* Supabase JS Client

### 🌐 Deployment

* Vercel (Frontend Hosting)

---

## ✨ Features

### 🛍️ Product System

* Fetch products dynamically from database
* Product detail page
* Responsive product cards

### 🛒 Cart Functionality

* Add to cart
* Remove from cart
* Update quantity (+ / -)
* Real-time cart updates

### 📦 Order System

* Place order
* Store order details in database
* Clear cart after checkout

### 🎨 UI / UX

* Amazon-like layout
* Responsive design
* Clean and modern interface

---

## 🗄️ Database Schema

### Products

* id
* name
* price
* image
* category
* description
* stock

### Cart

* id
* product_id
* quantity

### Orders

* id
* total
* created_at

### Order Items

* id
* order_id
* product_id
* quantity

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo/frontend
```

---

### 2️⃣ Install dependencies

```bash
npm install
```

---

### 3️⃣ Setup Environment Variables

Create a `.env` file:

```env
VITE_SUPABASE_URL=https://your-project-id.supabase.co
VITE_SUPABASE_KEY=your_anon_key
```

---

### 4️⃣ Run locally

```bash
npm run dev
```

---

## 🚀 Deployment (Vercel)

### Steps:

1. Push code to GitHub
2. Go to Vercel
3. Import your repository
4. Set:

```bash
Framework Preset: Vite
Build Command: npm run build
Output Directory: dist
```

---

### 🔑 Environment Variables (IMPORTANT)

Add in Vercel dashboard:

```bash
VITE_SUPABASE_URL=https://your-project-id.supabase.co
VITE_SUPABASE_KEY=your_anon_key
```

---

## 📁 Project Structure

```
frontend/
 ├── src/
 │    ├── components/
 │    ├── pages/
 │    ├── services/
 │    │    └── api.js
 │    ├── supabase.js
 │    ├── App.jsx
 │    └── main.jsx
 ├── public/
 └── package.json
```

---

## 🔥 Future Improvements

* 🔐 User Authentication (Supabase Auth)
* 🧾 Order History Page
* 💳 Payment Integration (Stripe / Razorpay)
* 🔍 Search & Filtering
* 🧑‍💼 Admin Dashboard

---

## 👨‍💻 Author

Chirag Pandit

---

## ⭐ Acknowledgements

* Supabase for backend services
* Vercel for hosting
* React ecosystem

---

## 📌 Note

This project is built for educational purposes and is not affiliated with Amazon.
