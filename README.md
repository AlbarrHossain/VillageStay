# 🌾 VillageStay – Authentic Rural Tourism Platform

*Hackathon Submission Project*  
Challenge 18 – Rural Tourism Marketplace

---

## 🧭 Project Overview

*VillageStay* is a full-stack web platform that connects *urban tourists* with *verified rural hosts* offering immersive village experiences — not just a place to stay, but a chance to live the culture.

🎯 Our goal is to empower rural communities, create sustainable micro-entrepreneurs, and preserve cultural heritage by bringing them online through a secure, transparent digital marketplace.

---

## ✨ Key Features

### 👤 Host Dashboard
- Add/edit listings: stays, meals, activities (e.g., pottery, farming, fishing)
- Create day-by-day itineraries
- Upload media (images, videos)
- Track bookings and earnings

### 🧳 Tourist Dashboard
- Browse village stays and filter by experiences
- View host itineraries, images, ratings
- Book immersive experience packages
- Leave reviews and upload photos

### 🔐 Authentication
- JWT-based login with *role-based access* (Tourist / Host / Admin)
- OTP-based email verification (optional)
  
### 💳 Payments & APIs
- Razorpay integration for secure payments
- Google Maps API to visualize host locations
- AWS S3 for image uploads

### 🧠 Innovation Features (Hackathon-Unique)
- ✅ AI-powered stay recommendations (based on interests)
- ✅ Cultural storytelling modules (host village stories)
- ✅ Volunteer onboarding portal for digitally onboarding villagers
- ✅ Eco-badge system for sustainable listings
- ✅ Multilingual support (demo: English + Hindi)

---

## 🔧 Tech Stack

| Layer       | Technology                 |
|-------------|-----------------------------|
| Frontend    | React.js, Tailwind CSS      |
| Backend     | Node.js, Express.js         |
| Database    | MongoDB, Mongoose           |
| Auth        | JWT, bcrypt, OTP/email      |
| Cloud       | AWS EC2, S3, MongoDB Atlas  |
| APIs        | Razorpay, Google Maps       |

---

## 🗂 Folder Structure

village-stay/

├── client/ # React frontend

├── server/ # Node.js backend

│ ├── routes/

│ ├── controllers/

│ ├── models/

│ ├── middlewares/

│ └── utils/

├── config/ # .env & keys

└── README.md

---

## 🚀 Getting Started (Dev Environment)

### 🔁 Prerequisites
- Node.js v16+
- MongoDB (Atlas or local)
- AWS S3 credentials
- Razorpay API key

### 📦 Backend Setup
```bash
cd server
npm install
npm run dev
```

### 💻 Frontend Setup
```bash
cd client
npm install
npm start
```

### 🌐 Environment Variables (.env)
```env
PORT=5000
MONGODB_URI=your_mongodb_url
JWT_SECRET=your_jwt_key
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret
EMAIL_SERVICE_API_KEY=your_email_key
```

### 📈 Future Roadmap
- Real-time chat between host and tourist
- Multilingual UI (English + Indian regional languages)
- Mobile app (React Native)
- Analytics dashboard for hosts
- Admin reporting & dispute resolution

### 🏆 Hackathon Impact Goals
- ✔ Empower rural micro-entrepreneurs
- ✔ Digitally onboard non-tech-savvy villagers
- ✔ Promote cultural preservation and eco-tourism
- ✔ Bridge the urban–rural digital divide

### 🤝 Credits
Built with ❤ by 
✩ Team AISD (Shahadik shaik, Ukam Sunil, Mohammad Albarr Hossain)!
