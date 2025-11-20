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
 <h4>Backend</h4>
<h5>backend/</h5>
<h5>│── controllers/</h5>
<h5>|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|── AuthController.js</h5>│     
<h5>│── models/</h5>
<h5>| &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;   ├── Otp.js </h5>
<h5>| &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;   │── User.js</h5>
<h5>│── DB/</h5>
<h5>│     └── db.js</h5>
<h5>│── server.js</h5>
<h5>│── .env</h5>


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

<li>dotenv</li>
</ul>
<h3>🔑 Environment Variables</h3>
<h5>Backend </h5> .env
<ul>
<li>uri=your_mongodb_url</li>
<li>JWT_SECRET=your_secret_key</li>
<li>EMAIL_USER=your_email</li>
<li>EMAIL_PASS=your_app_password</li>
<li>PORT=http://localhost:5173</li>
<li>OTP_EXPIRE_MIN = TIME</li>
</ul>

<h5>Frontend</h5> .env
VITE_API_URL=http://localhost:5000

Project Readme
📌 Authentication System with OTP & User Dashboard

A full-stack authentication system built using React, TailwindCSS, Node.js, Express, and MongoDB, with secure OTP verification, JWT authentication, and a protected user dashboard.

🚀 Features
🔐 Authentication

Signup with email OTP verification

Login using email & password

Forgot password with OTP verification

Reset password securely

JWT-based authentication

Password encrypted with bcryptjs

👤 User Dashboard

Fetch user details

Update user profile

Protected pages with JWT token

🌐 Frontend

React + Vite

TailwindCSS

React Router DOM

Axios for API calls

🗄 Backend

Express.js API

MongoDB + Mongoose

Nodemailer for sending OTP

bcryptjs for password encryption

dotenv for environment variables

📁 Project Structure
Backend
backend/
│── controllers/AuthController.js
│── models/
|    |-Otp.js 
|    |-User.js
│── DB/db.js
│── server.js
│── .env
Frontend
Selection deleted
frontend/
│── src/
│   │── components/
│         ├── Navigation/Navigation.jsx
│         ├── ProtectedRoute/ProtectedRoute.js
│         |──UserDashboard/Dashboard.jsx
│         ├── Login/Login.jsx
│         ├──SignUp/Signup.jsx
│         ├── Forget/ForgotPassword.jsx
│         ├── About/About.jsx
│         |── pages/├── Home.jsx
│   
│   
│── .env
│── vite.config.js
⚙️ Tech Stack
Frontend

React

Vite

TailwindCSS

Axios

React Router DOM

Backend

Node.js

Express.js

MongoDB

Mongoose

Nodemailer

bcryptjs

JWT

dotenv

🔑 Environment Variables
Backend .env
Selection deleted
uri=your_mongodb_url
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_app_password
PORT=http://localhost:5173
OTP_EXPIRE_MIN = TIME
Frontend .env
VITE_API_URL=http://localhost:5000


<h3>📡 API Endpoints</h3>
<h4>Auth Routes</h4>
Method	Endpoint	Description
POST	/api/auth/signup	Signup + Send OTP
POST	/api/auth/verify-signup-otp	Verify Signup OTP
POST	/api/auth/login	Login
POST	/api/auth/forgot-password	Send OTP for password reset
POST	/api/auth/verify-forgot-otp	Verify OTP
POST	/api/auth/reset-password	Reset password

<h4>User Routes</h4>
Method	Endpoint	Description
GET	/api/user-data/:email	Get logged-in user info
PUT	/api/update-user/:email	Update user info

<h3>🛡 Security Features</h3>
<ul>
<li>Password encryption using bcryptjs</li>

<li> Token-based authentication using JWT </li>

 <li>OTP verification for sensitive actions</li>

<li>Protected backend routes</li>

<li>Secure environment variables using dotenv</li>
</ul>

<h2>🏗 How to Run the Project</h2>
 <h3>Backend Setup</h3>
cd server
npm install
npm install bcryptjs body-parser cors dotenv express jsonwebtoken mongoose nodemailer
npm start

<h2>Frontend Setup</h2>
<h3Frontend Setup></h3>
cd frontend
npm install
npm install react-toastify axios react-hook-form @mui/material @emotion/react @emotion/styled lucide-react react-router-dom  tailwindcss @tailwindcss/vite
npm run dev

 
