# 💰 EMI Calculator (MERN Stack)

<div align="center">

# 🏦 Smart EMI Calculator

*A modern MERN Stack application that allows users to calculate loan EMI instantly by entering the loan amount, interest rate, and loan duration. The application automatically calculates the monthly EMI, total interest payable, total payment amount, and provides a detailed monthly repayment schedule with a clean and responsive interface.*

---

![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Express](https://img.shields.io/badge/Express.js-Backend-000000?style=for-the-badge&logo=express)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?style=for-the-badge&logo=node.js)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---  

# 📌 Overview

The **EMI Calculator** is a full-stack MERN application that simplifies loan repayment calculations. Users can enter the loan amount, annual interest rate, and loan duration, and the system instantly computes:

- Monthly EMI
- Total Interest Payable
- Total Amount Payable
- Monthly Payment Schedule

The application is built with a responsive and user-friendly interface, ensuring a seamless experience across desktop, tablet, and mobile devices.

---


# ✨ Features

### 💳 Loan Calculation

- Enter Loan Amount
- Enter Annual Interest Rate
- Select Loan Duration
- Support for Months and Years
- Real-time EMI Calculation

### 📊 Results

- Monthly EMI
- Total Interest
- Total Payment
- Principal Amount
- Interest Breakdown


### 📅 EMI Schedule

- Monthly Installment Details
- Opening Balance
- Principal Paid
- Interest Paid
- Closing Balance

### 🎨 UI Features

- Modern Design
- Responsive Layout
- Interactive Forms
- Clean Dashboard
- Mobile Friendly



---

# 🖥️ Tech Stack

## Frontend

- React.js
- Vite
- HTML5
- CSS3
- JavaScript (ES6+)
- Axios

## Backend

- Node.js
- Express.js

## Database

- MongoDB
- Mongoose

---


# 📂 Project Structure

```
EMI-Calculator/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
├── README.md
└── package.json
```

---


# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/emi-calculator.git
```

```bash
cd emi-calculator
```

---

## Install Frontend Dependencies

```bash
cd client
npm install
```

---

## Install Backend Dependencies

```bash
cd ../server
npm install
```

---


## Configure Environment Variables

Create a **.env** file inside the **server** folder.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string
```

---


## Run Backend

```bash
cd server
npm run dev
```

---

## Run Frontend

```bash
cd client
npm run dev
```

---


# 📐 EMI Formula

```
               P × R × (1 + R)^N
EMI = --------------------------------
       (1 + R)^N - 1
```

### Where

| Symbol | Description |
|---------|-------------|
| P | Principal Loan Amount |
| R | Monthly Interest Rate |
| N | Loan Duration in Months |

---


