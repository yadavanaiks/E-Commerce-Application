# E-commerce MERN Project

## 📌 Overview
This is a full-stack **E-commerce platform** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. The project provides a seamless online shopping experience, allowing users to browse products, add them to the cart, make payments, and track orders. The admin dashboard enables product and order management.

## 🎯 Features
### 🔹 User Features:
- ✅ User Authentication (Register/Login with JWT authentication)
- ✅ Browse products with search, filters, and sorting
- ✅ Add products to the shopping cart
- ✅ Secure checkout process with payment integration
- ✅ Order tracking & history

### 🔹 Admin Features:
- ✅ Manage products (Add, Update, Delete)
- ✅ Manage orders (View, Update status, Delete)
- ✅ Manage users (View, Promote to Admin, Delete)
- ✅ Dashboard for analytics & insights

## 🛠️ Tech Stack
### **Frontend:**
- React.js (Hooks, Context API/Redux for state management)
- React Router for navigation
- Tailwind CSS / Bootstrap for UI styling

### **Backend:**
- Node.js with Express.js
- MongoDB with Mongoose (Database)
- JWT for authentication
- Stripe / PayPal integration for payments

### **Deployment:**
- Frontend: Vercel / Netlify
- Backend: Render / Heroku
- Database: MongoDB Atlas

## ⚙️ Installation & Setup
Follow these steps to set up the project locally:

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/ecommerce-mern.git
cd ecommerce-mern
```

### **2️⃣ Install Dependencies**
#### Install Backend Dependencies:
```bash
cd backend
npm install
```

#### Install Frontend Dependencies:
```bash
cd frontend
npm install
```

### **3️⃣ Setup Environment Variables**
Create a `.env` file in the **backend** directory and add:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET=your_stripe_api_key
```

### **4️⃣ Run the Development Server**
#### Start Backend Server:
```bash
cd backend
npm run dev
```
#### Start Frontend Server:
```bash
cd frontend
npm start
```

### **5️⃣ Open in Browser**
Visit: `http://localhost:3000`

## 📂 Folder Structure
```
📦 ecommerce-mern
 ┣ 📂 backend
 ┃ ┣ 📂 models  # Mongoose models (User, Product, Order)
 ┃ ┣ 📂 routes  # API routes (Auth, Products, Orders)
 ┃ ┣ 📂 controllers  # Business logic for routes
 ┃ ┣ 📜 server.js  # Express server setup
 ┃ ┣ 📜 config.js  # Database connection & environment variables
 ┣ 📂 frontend
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 components  # Reusable React components
 ┃ ┃ ┣ 📂 pages  # Application pages (Home, Product, Cart, Checkout, Admin Dashboard)
 ┃ ┃ ┣ 📂 redux  # State management (if using Redux)
 ┃ ┃ ┣ 📜 App.js  # Main App component
 ┃ ┃ ┣ 📜 index.js  # React root file
 ┃ ┣ 📜 package.json  # Frontend dependencies
 ┣ 📜 README.md  # Project documentation
```

## 🚀 Deployment
1. Deploy **backend** on **Render / Heroku**
2. Deploy **frontend** on **Vercel / Netlify**
3. Use **MongoDB Atlas** as a cloud database
