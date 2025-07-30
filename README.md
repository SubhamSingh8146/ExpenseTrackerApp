# 💸 Expense Tracker – MERN Stack Application

A full-featured MERN (MongoDB, Express, React, Node.js) web application that allows users to track, visualize, and export their personal expenses with ease. The app includes secure authentication, dynamic charts, and downloadable reports in Excel and PDF formats.

---

## 🚀 Features

- 🔐 **User Authentication** (Login/Register with JWT)
- 💰 **Add, Edit, Delete Expenses**
- 📊 **Visual Graphs** (Pie Charts & Bar Graphs for categorized spending)
- 📈 **Dynamic Filtering** (by date, category, etc.)
- 📥 **Download Excel Reports** (with all expense data)
- 🧾 **Export Pie Chart as PDF**
- ☁️ **Deployed Frontend on Vercel**
- 🌐 **Backend with Express & MongoDB (Hosted on Render or other)**

---

## 🧑‍💻 Tech Stack

| Frontend        | Backend         | Database |
|-----------------|------------------|----------|
| React.js        | Node.js          | MongoDB  |
| Axios           | Express.js       | Mongoose |
| Chart.js / Recharts | JWT (Auth)  |           |
| html2canvas + jspdf (PDF export) | CORS, bcrypt |      |

---

## 📂 Project Structure

expense-tracker/
├── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── index.js
│ └── .env
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ └── App.js
│ └── public/
├── README.md
└── package.json

yaml
Copy
Edit

---

## ⚙️ Installation

### 🔽 Clone the Repository
```bash
git clone https://github.com/SubhamSingh8146/ExpenseTrackerApp.git
cd ExpenseTrackerApp
🔧 Backend Setup
bash
Copy
Edit
cd backend
npm install
# Add your .env file with MongoDB URI and JWT secret
npm start
💻 Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
🌐 Live Demo
Frontend: https://expense-frontend-chi.vercel.app
Backend: (Add your deployed backend URL here, e.g., Render or Vercel)

📸 Screenshots
(You can add screenshots here using Markdown syntax)

markdown
Copy
Edit
![Dashboard](screenshots/dashboard.png)
![PDF Export](screenshots/pdf-export.png)
📦 Dependencies
React

Chart.js or Recharts

Axios

Express

MongoDB & Mongoose

bcrypt, jsonwebtoken

xlsx, html2canvas, jspdf

🙌 Author
Subham Singh
GitHub: @SubhamSingh8146

