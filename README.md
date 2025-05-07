
# 🛒 Amazon Mania

Amazon Mania is a full-stack e-commerce web application inspired by Amazon. It features product listings, shopping cart, checkout, user authentication, admin dashboard, and a simulated **10-minute delivery option**.

---

## 🚀 Features

- 🛍️ Browse and search products
- 🔐 User authentication (Login, Signup, JWT)
- 🛒 Shopping cart and wishlist
- 💳 Checkout with fake payment integration
- 📦 Simulated 10-minute delivery option
- 🧑‍💼 Admin dashboard to manage products and orders
- 🔄 Order tracking
- 🔍 Product rating and reviews (basic)

---

## 🧰 Tech Stack

| Frontend       | Backend             | Database | Auth     | Deployment          |
|----------------|---------------------|----------|----------|---------------------|
| React + Tailwind CSS | Node.js + Express | MongoDB  | JWT      | Vercel / Render / MongoDB Atlas |

---

## 📦 Folder Structure

```
amazon-mania/
├── client/        # React frontend
├── server/        # Node.js + Express backend
└── README.md
```

---

## 🛠️ Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/amazon-mania.git
cd amazon-mania
```

### 2. Setup Backend

```bash
cd server
npm install
# Create a .env file with MONGODB_URI, JWT_SECRET
npm start
```

### 3. Setup Frontend

```bash
cd ../client
npm install
npm run dev
```

Frontend runs at `http://localhost:5173` and backend at `http://localhost:5000`.

---

## 🌐 Deployment

- **Frontend**: Vercel (connect `client/`)
- **Backend**: Render or Railway (connect `server/`)
- **DB**: MongoDB Atlas

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Acknowledgments

Inspired by Amazon’s core functionality, but built from scratch for educational purposes.
