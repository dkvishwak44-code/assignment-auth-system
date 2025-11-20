<h1>📌 Authentication System with OTP & User Dashboard</h1>


A full-stack authentication system built using React, TailwindCSS, Node.js, Express, and MongoDB, featuring secure OTP verification, JWT authentication, and a protected user dashboard.

<h3>🚀 Features</h3>
🔐 Authentication

Signup with email OTP verification

Login using email & password

Forgot password with OTP OTP verification

Reset password securely

JWT-based authentication

Password encrypted with bcryptjs

👤 User Dashboard

Fetch user details

Update user profile

Protected pages using JWT token

<h3>🌐 Frontend </h3>

React (Vite)

TailwindCSS

React Router DOM

Axios

🗄 Backend

Express.js

MongoDB + Mongoose

Nodemailer for OTP

bcryptjs

dotenv


<h3>📁 Project Structure</h3>
Backend
backend/
│── controllers/
│     └── AuthController.js
│── models/
│     ├── Otp.js 
│     └── User.js
│── DB/
│     └── db.js
│── server.js
│── .env


<h3>Frontend</h3>

frontend/
│── src/
│ │── components/
│ ├── Navigation/Navigation.jsx
│ ├── ProtectedRoute/ProtectedRoute.js
│ |──UserDashboard/Dashboard.jsx
│ ├── Login/Login.jsx
│ ├──SignUp/Signup.jsx
│ ├── Forget/ForgotPassword.jsx
│ ├── About/About.jsx
│ |── pages/├── Home.jsx
│
│
│── .env
│── vite.config.js

<h3>⚙️ Tech Stack</h3>
 <h4>Frontend</h4>
 <ul>

<li>React</li>

<li>Vite</li>

<li>TailwindCSS</li>

<li>Axios</li>

<li>React Router DOM</li>
</ul>

<h4>Backend</h4>
<ul>

<li>Node.js</li>

<li>Express.js</li>

<li>MongoDB</li>

<li>Mongoose</li>

<li>Nodemailer</li>

<li>bcryptjs</li>

<li>JWT</li>

dotenv
</ul>

