# React Native Ecommerce App

A full-stack Ecommerce Mobile Application built using **React Native** for the frontend and **Node.js + Express.js** for the backend, with **MongoDB** as the database.

This app includes authentication, product management, cart functionality, secure payments, social logins, and image uploads.

---

## 🚀 Tech Stack

### Frontend (Mobile App)
- React Native
- React Navigation
- Axios
- Async Storage

### Backend (API Server)
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer (Image Uploads)

### Additional Integrations
- Payment Gateway Integration (Stripe)
- Social Login
- Cloud Image Storage

---

## 📂 Project Structure

```
/client      → React Native App
/server      → Node + Express Backend
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/react-native-ecommerce.git
cd react-native-ecommerce
```

---

### 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create a `.env` file inside the `/server` folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PAYMENT_SECRET=your_payment_gateway_key
```

Start the backend server:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd client
npm install
```

Run the app:

```bash
npx react-native run-android
# or
npx react-native run-ios
```

