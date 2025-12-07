# Zerodha Clone – Mini Trading App

A simple and clean web application inspired by Zerodha and its Kite trading dashboard.  
This project focuses mainly on building the UI with React and integrating a basic backend using Node.js, Express, and MongoDB.

## 🎯 Project Overview

Zerodha Clone allows users to:
- Explore the Zerodha-like homepage (About, Products, Pricing, Support)
- Access the **Kite demo dashboard** from the Products section
- View different trading products in the UI
- Place Buy/Sell orders (saved in MongoDB)

No login or authentication — the app is accessible to all users.

---

## 🚀 Features

- Zerodha-style responsive frontend (React + Bootstrap)
- Separate **Kite Dashboard** built using React
- Market products with Buy/Sell interface
- Orders saved in MongoDB
- Holdings, Positions, Orders UI (not fully functional)
- Clean routing and UI structure
- Backend API using Node.js + Express

---

## 🧱 Tech Stack

- **Frontend:** React.js, Bootstrap, React Router  
- **Dashboard:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Others:** Axios, CORS, dotenv  

---

## ✅ Installation & Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/zerodha-clone.git
    ```

2. Navigate to each folder (frontend, dashboard, backend) and install dependencies:
    ```bash
    cd frontend
    npm install
    ```
    ```bash
    cd dashboard
    npm install
    ```
    ```bash
    cd backend
    npm install
    ```

3. Create a `.env` file inside the **backend** folder:
    ```env
    MONGODB_URL=your_mongodb_url
    ```

4. Start each service:
    ```bash
    cd frontend
    npm start
    ```
    ```bash
    cd dashboard
    npm start
    ```
    ```bash
    cd backend
    npm start
    ```

5. Open the app in your browser:
    - Frontend: `http://localhost:3000`
    - Dashboard: `http://localhost:3001` (if separate port)
    - Backend: `http://localhost:3002`

---

## 🌐 Live Demo

Visit the live Zerodha Clone here:  
👉 **[https://zerodha-clone-zilj.onrender.com]**

To explore the Kite demo dashboard:  
Go to **Products → Kite → Try Demo** inside the website.

---

## ⚡ Dependencies

```bash
npm install express mongoose dotenv cors axios react-router-dom body-parser
