# 🎨 Imagify – Full Stack Text-to-Image Generator SaaS App


![Netlify Deploy](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=netlify)  


**Live App:** [https://text-to-image-generator-saas-reactapp.netlify.app/](https://text-to-image-generator-saas-reactapp.netlify.app/) 

**Backend API:** Hosted on Render  

**GitHub Repo:** [Anitha-Chava/Full-Stack-Text-to-Image-Generator-SaaS-React-App](https://github.com/Anitha-Chava/Full-Stack-Text-to-Image-Generator-SaaS-React-App)


---

## 📌 Overview

**Imagify** is a full-stack SaaS application that uses AI APIs (like ClipDrop) to convert text prompts into realistic images. It supports user authentication, subscriptions, payment gateways (Razorpay/Stripe), and advanced image download functionality.

---

## ✨ Features

✅ AI-Powered Text-to-Image Generation  

✅ Secure User Authentication (JWT-based)  

✅ MongoDB Atlas for Cloud Database  

✅ Razorpay & Stripe Payment Integration  

✅ Environment-Safe with `.env` Variables  

✅ Fully Responsive UI using React + Tailwind CSS  

✅ Protected Routes and Subscription Handling  

✅ Real-Time Image Preview & Download  

✅ Deployment: Netlify (frontend) + Render (backend)


---



## 🔧 Tech Stack

### 🔹 Frontend

- [React.js](https://reactjs.org/)
  
- [Tailwind CSS](https://tailwindcss.com/)

- [React Router DOM](https://reactrouter.com/)


### 🔹 Backend

- [Node.js](https://nodejs.org/)
  
- [Express.js](https://expressjs.com/)
  
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
  
- [Mongoose](https://mongoosejs.com/)
  
- [JWT (jsonwebtoken)](https://jwt.io/)
  

### 🔹 APIs

- [ClipDrop API](https://clipdrop.co/apis)
  
- [Razorpay](https://razorpay.com/)
  
- [Stripe](https://stripe.com/)

---

## 🚀 Deployment

### 🔸 Frontend – Netlify

- Build Command:
  
  ```bash
     npm run build

- Publish Directory:
  
      dist
- Environment Variable:

      REACT_APP_API_URL = https://imagify-server-aq02.onrender.com
    
🔸 Backend – Render

- Root Directory: server

- Build Command:

      npm install
    
- Start Command:

      npm start
- Environment Variables:

| **Key**               | **Value**                                                                                                                        |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------|
| JWT_SECRET            | secret#text                                                                                                                      |
| MONGODB_URI           | mongodb+srv://anithachava:anithachava1234@cluster0.tzp0ipt.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0             |
| CLIPDROP_API          | 889299a89b4d81dde2948986821db22e7af13eebfe1318fb7382642e13a318bc9c34d95c8e383dba84bd706045e76232                                 |
| CURRENCY              | INR                          |
| RAZORPAY_KEY_ID       | encrepted        |
| RAZORPAY_KEY_SECRET   | encrepted   |
| STRIPE_SECRET_KEY     | encrepted       |


📁 Folder Structure


Full-Stack-Text-to-Image-Generator-SaaS-React-App

│

├── client/                 # React Frontend (Vite-based)

│   ├── public/

│   └── src/

│       ├── assets/

│       ├── components/

│       ├── pages/

│       ├── App.jsx

│       └── main.jsx

│

├── server/                 # Node.js + Express Backend

│   ├── config/

│   ├── controllers/

│   ├── models/

│   ├── routes/

│   ├── utils/

│   └── server.js

│

└── README.md



💻 Local Setup

- Clone the Repository

      git clone https://github.com/Anitha-Chava/Full-Stack-Text-to-Image-Generator-SaaS-React-App.git

- Type this command in terminal
  
   cd Full-Stack-Text-to-Image-Generator-SaaS-React-App

- Install Client Dependencies


      cd client

      npm install

      npm run dev


- Install Server Dependencies


      cd ../server

      npm install

      npm run start

- Create a .env file inside /server



🛡️ License

This project is licensed under the MIT License. Feel free to use and modify with credit.



![Netlify Status](https://api.netlify.com/api/v1/badges/3e6c0d0e-b626-4a2a-8a89-fcf99977e0d9/deploy-status)

![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)

![Express](https://img.shields.io/badge/Backend-Express.js-blue)

![React](https://img.shields.io/badge/Frontend-React-orange)

![Node](https://img.shields.io/badge/Runtime-Node.js-lightgrey)



## 🚀 Live Demo

🌐 **Frontend**: [View Live](https://text-to-image-generator-saas-reactapp.netlify.app/)

🎥 **Video Demo**: [Watch on LinkedIn](https://www.linkedin.com/feed/) *(Replace with your actual LinkedIn video link)*

> This SaaS app converts user prompts into AI-generated images using the ClipDrop API, allows payment via Razorpay, and includes full authentication and database integration with MongoDB.


Linkedin: [Anitha Chava](www.linkedin.com/in/anitha-chava)




📧 Connect on LinkedIn

⭐️ Give a Star

If you like this project, consider giving it a ⭐️ on GitHub to support the developer!










