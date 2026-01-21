# 💊 Smart Drug Inventory & Supply Chain Tracker

A **full-stack MERN web application** designed to help pharmacies, distributors, and suppliers manage drug inventory efficiently, track medicine movement across the supply chain, and ensure secure, role-based access for all users.

---

## 🚀 Project Overview

The **Smart Drug Inventory & Supply Chain Tracker** is built to solve real-world challenges in pharmaceutical inventory management such as:

* Stock shortages and overstocking
* Expired medicine tracking
* Secure access for different user roles
* Transparent supply chain flow

This system provides **real-time inventory updates**, **role-based dashboards**, and **secure authentication**, making it suitable for production-style use cases.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* JavaScript (ES6+)
* Axios

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication

### Tools & DevOps

* Git & GitHub
* Postman
* Docker (Optional)

---

## ✨ Key Features

### 🔐 Authentication & Security

* JWT-based login and registration
* Protected routes for secure access
* Role-based authorization (RBAC)

### 👥 Role-Based Dashboards

* **Admin:** Manage users, view system-wide analytics
* **Supplier:** Add medicines, track shipments
* **Pharmacist:** Monitor stock, request supplies, track expiry

### 📦 Inventory Management

* Add, update, and delete medicines
* Real-time stock level updates
* Low-stock and expiry alerts

### 🔄 Supply Chain Tracking

* Track medicine movement from **Supplier → Distributor → Pharmacy**
* Maintain transaction history and audit logs

### 📱 Responsive UI

* Mobile-friendly design using Tailwind CSS
* Clean dashboards with data tables and filters

---

## 📂 Project Structure

```
smart-drug-inventory/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js (v16+ recommended)
* MongoDB (Local or Atlas)
* Git

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Nithin152004/smart-drug-inventory.git
cd smart-drug-inventory
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Run the backend server:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
npm start
```

Frontend will run on:

```
http://localhost:3000
```

---

## 🔄 API Endpoints (Sample)

### Auth Routes

```
POST /api/auth/register
POST /api/auth/login
```

### Inventory Routes

```
GET    /api/medicines
POST   /api/medicines
PUT    /api/medicines/:id
DELETE /api/medicines/:id
```

### Supply Chain Routes

```
POST /api/shipments
GET  /api/shipments
```

---

## 🧪 Testing

* API tested using **Postman**
* Manual UI testing across mobile and desktop views

---

## 📸 Screenshots (Optional)

Add screenshots here:

```
/screenshots/dashboard.png
/screenshots/inventory.png
/screenshots/login.png
```

---

## 📈 Future Enhancements

* Barcode / QR scanning for medicines
* Email & SMS alerts for low stock and expiry
* Analytics dashboard with charts
* Role-based approval workflows
* Multi-warehouse support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Nithin D**
GitHub: [https://github.com/Nithin152004](https://github.com/Nithin152004)
LinkedIn: [https://www.linkedin.com/in/nithin-d-57810b25b](https://www.linkedin.com/in/nithin-d-57810b25b)

---

> If you found this project useful, please ⭐ star the repository and share your fee
