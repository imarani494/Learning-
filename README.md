# 🧠 EduLearn – Online Learning Platform

> A modern e-learning platform built with **React.js**, **Node.js**, **Express.js**, and **MongoDB** — empowering students and instructors through an engaging and seamless learning experience.

---

## 👨‍💻 Author
**Developed by [Imaran](https://github.com/imarani494)**  
Full Stack MERN Developer | Passionate about scalable web apps & clean architecture

---

## 🚀 Features

### 👤 User Management
- Secure **JWT-based authentication**
- **Role-based access control** (Student, Instructor, Admin)
- Customizable user profiles with avatars
- Secure password hashing with **bcrypt**
- Forgot/reset password functionality

### 📚 Course Management
- Instructors can **create, update, and publish** courses
- Organized **course categories** (Programming, Design, Business, etc.)
- Students can **rate and review** courses
- **Draft/Publish** mode for flexible course creation

### 🎓 Learning Experience
- Streamlined **video lessons** & text-based content
- **Progress tracking** & completion certificates
- Multi-format lesson support: video, quiz, text, PDF, assignments
- Real-time **enrollment tracking**

### 📊 Dashboards & Analytics
- **Student dashboard**: Track enrolled courses & progress
- **Instructor dashboard**: Manage courses & students
- **Admin dashboard**: Monitor users, courses, and global analytics

---

## 🛠️ Technology Stack

| Layer | Tech |
|:------|:-----|
| Frontend | React.js, React Router, React Query, Tailwind CSS, Lucide Icons, React Hot Toast |
| Backend | Node.js, Express.js, Mongoose, JWT, bcryptjs, Helmet, Express Validator |
| Database | MongoDB (Atlas / Local) |
| Tools | ESLint, Prettier, Nodemon, Vercel, Render |

---

## 📁 Project Structure

online-learning/
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── server.js
│ ├── package.json
│ └── .env.example
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── context/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── App.js
│ │ └── index.js
│ ├── public/
│ ├── package.json
│ └── tailwind.config.js
└── package.json


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/imarani494/Online-Learning.git
cd Online-Learning

2️⃣ Install Dependencies
# Root
npm install

# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install

3️⃣ Configure Environment Variables

Create .env inside /backend:

MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/elearning
JWT_SECRET=yourSuperSecretKeyHere
JWT_EXPIRE=7d
PORT=5000
NODE_ENV=development
CLIENT_URL=http://localhost:3000

🧑‍💻 Running the App
Development Mode
npm run server       # Run backend only
npm run client       # Run frontend only
npm run dev          # Run both concurrently (if configured)

Production Mode
cd frontend
npm run build
cd ../backend
npm start

🧪 Demo Accounts
Role	Email	Password
Student	student@demo.com
	password123
Instructor	instructor@demo.com
	password123
Admin	admin@demo.com
	password123
🌐 Deployment Guide
Frontend (Vercel / Netlify)
cd frontend
npm run build


Deploy /build folder to your hosting platform.

Backend (Render / Railway / Heroku)

Set these environment variables:

MONGODB_URI
JWT_SECRET
CLIENT_URL
NODE_ENV=production
PORT=5000

🧠 Common Issues
Issue	Solution
❌ CORS Error	Check CLIENT_URL in .env and server.js
⚠️ MongoDB not connecting	Verify URI & whitelist IP in Atlas
🔑 JWT Auth failing	Ensure JWT_SECRET matches
🧩 Build failed	Delete node_modules and reinstall
🧰 Development Guidelines

Use Prettier + ESLint for formatting

Follow Conventional Commits

Keep components modular

Always handle errors gracefully

💡 Future Enhancements

Dark/Light mode toggle

AI-based course recommendation

Instructor earnings dashboard

Email & push notifications

🤝 Contributing

Contributions welcome 💬

Fork repo

Create branch (feature/new-feature)

Commit & push changes

Open a Pull Request

📜 License

MIT License © 2025 — Developed by Imaran

🎓 Live Demo

🌍 EduLearn Frontend (Vercel)


---

### **3️⃣ Save and close the file**

---

### **4️⃣ Commit and push to GitHub**
```bash
git add README.md
git commit -m "Update README.md with Imaran details"
git push origin main

✅ Result

Now when you open your GitHub repo
👉 https://github.com/imarani494/Online-Learning

you’ll see this beautiful professional README showing all sections properly formatted.
