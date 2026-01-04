# 💰 Budget Tracker (MERN Stack)

A full-stack **Budget & Expense Tracking Web Application** built using the **MERN stack** (MongoDB, Express, React, Node.js).  
The app allows users to securely track income and expenses, manage transactions, and view their financial data across devices.

---

## 🚀 Live Demo

- **Frontend (Vercel):** https://budget-tracker-delta-olive.vercel.app/ 
- **Backend (Render):** https://expense-tracker-backend-m3v1.onrender.com

---

## ✨ Features

- 🔐 **JWT-based Authentication**
- ➕ Add income & expense transactions
- ✏️ Edit existing transactions
- 🗑️ Delete transactions (protected)
- 📊 **Filter & sort transactions**
- 🌙 **Light / Dark mode support**
- 🚫 Duplicate submission prevention
- ☁️ Cloud-hosted backend & database
- 📱 Responsive UI (mobile-friendly foundation)

---

## 🛠️ Tech Stack

### Frontend
- React (CRA)
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose
- JWT Authentication

### Deployment
- **Frontend:** Vercel
- **Backend:** Render
- **Database:** MongoDB Atlas

---

budget-tracker/
├── frontend/
│ ├── src/
│ ├── public/
│ ├── .env # local only (ignored)
│ ├── .env.example # committed
│ └── package.json
│
├── backend/
│ ├── server.js
│ ├── middleware.js
│ ├── User.js
│ ├── .env # local only (ignored)
│ ├── .env.example # committed
│ └── package.json
│
└── README.md

🧪 Running Locally
1️⃣ Clone the repository
git clone https://github.com/<your-username>/budget-tracker.git
cd budget-tracker

2️⃣ Install dependencies
Backend
cd backend
npm install

Frontend
cd ../frontend
npm install

3️⃣ Start the application
Start Backend
cd backend
node server.js
Backend runs on: http://localhost:5000

Start Frontend
cd frontend
npm start
Frontend runs on: http://localhost:3000

📜 License
This project is licensed under the MIT License.
