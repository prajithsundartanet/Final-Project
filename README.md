# Final Project

This project is a full-stack web application with **Backend**, **Frontend**, and **Admin Panel** modules. Follow the instructions below to set up and run the project on your local machine.

---

## 📌 Prerequisites

Make sure the following are installed on your system:

- [Node.js](https://nodejs.org/en/download/)  
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register) account  
- [Cloudinary](https://cloudinary.com/) account (for file storage)  
- (Optional) [Stripe](https://dashboard.stripe.com/register) account  
- (Optional) [Razorpay](https://accounts.razorpay.com/auth/) account  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/prajithsundartanet/Final-Project.git
cd Final-Project
```

### 2. Backend Setup
1. Open the project in **VS Code**.  
2. Open terminal in the `backend` folder:  
   ```bash
   cd backend
   npm install
   ```
3. Configure environment variables in `backend/.env`:
   ```env
   CLOUDINARY_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_SECRET=your_secret_key

   MONGO_URI=your_mongodb_connection_string

   STRIPE_SECRET=your_stripe_secret_key   # optional
   RAZORPAY_KEY_ID=your_razorpay_key_id   # optional
   RAZORPAY_SECRET=your_razorpay_secret   # optional
   ```
   ⚠️ **Note**: Do not use `@` in MongoDB password, and do not add `/` at the end of the MongoDB URI.
4. Run the backend:
   ```bash
   npm run server
   ```

---

### 3. Frontend Setup
1. Open terminal in the `frontend` folder:  
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
2. Open [http://localhost:5173](http://localhost:5173) in your browser.

---

### 4. Admin Panel Setup
1. Open terminal in the `admin` folder:  
   ```bash
   cd admin
   npm install
   npm run dev
   ```
2. Open [http://localhost:5174](http://localhost:5174) in your browser.

---

## 🚀 Running the Project
- Make sure the **Backend** is running before starting the **Frontend** or **Admin Panel**.  
- Default URLs:  
  - Backend: running via `npm run server`  
  - Frontend: [http://localhost:5173](http://localhost:5173)  
  - Admin: [http://localhost:5174](http://localhost:5174)  

---
