# 🩸 BloodLink Backend

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge\&logo=express\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge\&logo=mongodb\&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge\&logo=jsonwebtokens\&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### 🚑 Backend API for BloodLink Platform

A scalable REST API backend powering the BloodLink blood donation ecosystem.

</div>

---

# ✨ Features

✅ User Authentication & Authorization
✅ JWT Secure Login System
✅ Blood Donor Management
✅ Blood Request Handling
✅ MongoDB Database Integration
✅ RESTful API Architecture
✅ Error Handling Middleware
✅ Role-Based Access Control
✅ Environment Variable Configuration
✅ Scalable Backend Structure

---

# 🛠 Tech Stack

| Technology | Purpose               |
| ---------- | --------------------- |
| Node.js    | Runtime Environment   |
| Express.js | Backend Framework     |
| MongoDB    | Database              |
| Mongoose   | ODM                   |
| JWT        | Authentication        |
| bcrypt.js  | Password Hashing      |
| dotenv     | Environment Variables |

---

# 📂 Project Structure

```bash id="7w6fko"
blood_link_backend/
├── controllers/
├── middleware/
├── models/
├── routes/
├── config/
├── utils/
├── .env
├── server.js
└── package.json
```

---

# 🚀 Getting Started

## Prerequisites

Before running the project, make sure you have:

* Node.js installed
* MongoDB installed or MongoDB Atlas account
* npm or yarn package manager

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash id="4jxm0q"
git clone https://github.com/magarohan/blood_link_backend.git
```

## 2️⃣ Navigate to Project Folder

```bash id="o8zkx2"
cd blood_link_backend
```

## 3️⃣ Install Dependencies

```bash id="r2j6i5"
npm install
```

---

# 🔐 Environment Variables

Create a `.env` file in the root directory:

```env id="xkh0po"
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

# ▶️ Run the Server

## Development Mode

```bash id="1ps9s9"
npm run dev
```

## Production Mode

```bash id="f7z60z"
npm start
```

---

# 🌐 API Endpoints

## Authentication

| Method | Endpoint             | Description   |
| ------ | -------------------- | ------------- |
| POST   | `/api/auth/register` | Register User |
| POST   | `/api/auth/login`    | Login User    |

---

## Donors

| Method | Endpoint          | Description      |
| ------ | ----------------- | ---------------- |
| GET    | `/api/donors`     | Get All Donors   |
| POST   | `/api/donors`     | Add Donor        |
| GET    | `/api/donors/:id` | Get Single Donor |
| PUT    | `/api/donors/:id` | Update Donor     |
| DELETE | `/api/donors/:id` | Delete Donor     |

---

## Blood Requests

| Method | Endpoint        | Description      |
| ------ | --------------- | ---------------- |
| GET    | `/api/requests` | Get All Requests |
| POST   | `/api/requests` | Create Request   |

---

# 📦 API Response Example

```json id="m8wl9m"
{
  "success": true,
  "message": "User registered successfully",
  "token": "jwt_token_here"
}
```

---

# 🔒 Security Features

* Password Hashing with bcrypt
* JWT Authentication
* Protected Routes
* Environment Variables
* Input Validation
* Error Handling Middleware

---

# 🧪 Running Tests

```bash id="x3h72n"
npm test
```

---

# 🚀 Deployment

You can deploy this backend on:

* Render
* Railway
* Vercel
* Cyclic
* DigitalOcean
* AWS EC2

---

# 📈 Future Improvements

* Email Verification
* SMS Notifications
* Real-time Socket.IO Integration
* Docker Support
* API Rate Limiting
* Swagger API Documentation
* CI/CD Pipeline

---

# 🤝 Contributing

Contributions are welcome!

## Steps

1. Fork the repository

2. Create a feature branch

```bash id="7wo0t3"
git checkout -b feature/YourFeature
```

3. Commit changes

```bash id="jlwm0w"
git commit -m "Add YourFeature"
```

4. Push to GitHub

```bash id="jlwm0x"
git push origin feature/YourFeature
```

5. Create a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

### Rohan Magar

* GitHub: https://github.com/magarohan

---

<div align="center">

### ❤️ Powering Blood Donations Through Technology

⭐ Star this repository if you found it useful!

</div>
