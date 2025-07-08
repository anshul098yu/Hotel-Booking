# 🏨 Hotel Booking Management System

A full-featured **Hotel Booking Management System** built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) that allows users to book hotel rooms, view recent searches, and manage their bookings. Hotel owners can register hotels, upload room details with images, and manage availability.

---
👉 **Live Preview:** [https://hb-gs.vercel.app/](https://hb-gs.vercel.app/)
## 🚀 Features

### 👤 User Side
- Register & Login with secure authentication
- Search hotels by location, availability, and rating
- View detailed room info, photos, and amenities
- Book rooms and track your bookings
- View and manage past and upcoming bookings
- See recent searches for quick access

### 🏨 Hotel Owner Side
- Owner registration and login
- Register new hotels and add room details
- Upload images and set room prices
- Manage room availability and bookings
- View analytics on room occupancy

### 🔐 Authentication & Security
- JWT-based authentication
- Role-based access control (User / Hotel Owner)
- Clerk / Firebase (optional) for advanced auth features
- Webhooks (e.g., Svix) for syncing user data securely

---

## 🛠️ Tech Stack

| Layer        | Technology       |
|--------------|------------------|
| Frontend     | React.js         |
| Backend      | Node.js, Express.js |
| Database     | MongoDB (Mongoose) |
| Auth         | JWT / Clerk / Firebase |
| Image Upload | Cloudinary / Firebase Storage |
| DevOps       | Docker, GitHub Actions (optional) |
| Docs         | Swagger for API Documentation |

---


---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)
- (Optional) Docker & Docker Compose

### Backend (Express)
```bash
cd server
npm install
npm run dev

### Frontend (React)
cd client
npm install
npm start

Docker (Optional)
docker-compose up --build

🔐 Environment Variables
Create a .env file in the server/ folder:
PORT=5000
MONGODB_URI=mongodb+srv://your-db-url
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
CLERK_API_KEY=your_clerk_key   # Optional





