# User Authentication & Authorization System

A secure user authentication and authorization system built using **Node.js, Express, MongoDB, and EJS**.  
This project demonstrates session-based authentication with protected routes and logout functionality.

---

## 🚀 Features

- User Registration
- User Login
- Password Hashing (bcrypt)
- Session-based Authentication
- Protected Dashboard Route
- Logout with Session Destruction
- MVC Folder Structure
- Clean UI with EJS Templates

---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS
- express-session
- bcryptjs
- HTML, CSS

---

## 📂 Project Structure

Backend/
├── src/
│ ├── routes/
│ ├── middleware/
│ ├── views/
│ ├── public/
│ └── app.js
├── server.js
├── package.json
└── .env

yaml
Copy code

---

## ⚙️ How to Run Locally

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/user-authentication-system.git
Install dependencies

bash
Copy code
npm install
Create .env file

ini
Copy code
PORT=3000
MONGO_URI=your_mongodb_connection
SESSION_SECRET=your_secret_key
Start the server

bash
Copy code
npm run dev
Open browser

bash
Copy code
http://localhost:3000/login
🔐 Authentication Flow
Unauthorized users cannot access /dashboard

Session is created after login

Logout destroys session and clears cookies

Back button access is prevented

📸 Screenshots
Add screenshots here

👨‍💻 Author
Dhiraj Kumar

📌 Future Improvements
JWT-based authentication

Role-based authorization

Flash messages

Deployment (Render / Railway)

yaml
Copy code

---

# 🎯 FINAL CHECKLIST BEFORE PUSH
✔ `.env` not pushed  
✔ `node_modules` ignored  
✔ README added  
✔ Clean commits  
✔ Project runs locally  

---

## 💼 RESUME TIP
Add this project as:

> **User Authentication & Authorization System**  
> Built a secure session-based authentication system using Node.js, Express, MongoDB, and EJS with protected routes and logout functionality.

---

If you want next:
- 🎯 Resume bullet points
- 💬 Interview questions from this project
- 🚀 Deploy to Render
- 🔐 JWT version

Just tell me what you want next 👌
