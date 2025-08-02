<h1 align="center">🌍 Wanderlust – Travel Listing Web Application</h1>

<p align="center">
  A full-stack travel platform where users can explore, list, and manage accommodations securely. Built using the MERN stack with Mapbox and Cloudinary integrations.
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Backend-Express.js-blue" />
  <img src="https://img.shields.io/badge/Database-MongoDB-green" />
  <img src="https://img.shields.io/badge/Auth-JWT%20%7C%20Bcrypt-yellow" />
  <img src="https://img.shields.io/badge/View-Engine-EJS-critical" />
</div>

---

## ✨ Overview

**Wanderlust** is a dynamic web platform where users can:
- 🔐 Register and login securely
- 🏠 Post and manage their own accommodation listings
- 📍 Visualize listing locations on interactive maps
- 📷 Upload multiple property images with Cloudinary
- ✍️ View, edit, and delete listings via intuitive UI

---

## 🚀 Live Demo

> 🔗 Coming Soon – Add your hosted link here  
> 💡 Tip: Use [Render](https://render.com), [Vercel](https://vercel.com), or [Cyclic](https://www.cyclic.sh/) for deployment

---

## 📸 Screenshots

> Add high-quality images like:
> - 🖼 Homepage
> - ✍️ Listing Form
> - 🧭 Map View
> - 📱 Mobile Responsive Views

---

## 🛠 Tech Stack

| Layer       | Technologies Used                           |
|-------------|----------------------------------------------|
| Frontend    | EJS, Bootstrap 5, HTML, CSS, JavaScript      |
| Backend     | Node.js, Express.js                          |
| Database    | MongoDB (with Mongoose ORM)                  |
| Auth        | JWT, bcrypt, express-session, passport       |
| Upload      | Multer, Cloudinary                           |
| Maps        | Mapbox GL JS                                 |
| Tools       | dotenv, method-override, connect-flash       |

---

## 💡 Key Features

### 👤 Authentication
- Secure JWT login & registration
- Password encryption with bcrypt
- Session & flash message handling

### 🏠 Listing Management
- Add, edit, delete accommodations
- Upload multiple images per listing
- Display listing locations with Mapbox

### 📍 Interactive Map Integration
- Auto geocode locations on listing creation
- Show listings on a dynamic map with markers

### 📋 UI/UX Enhancements
- Clean and responsive layout using Bootstrap
- Flash alerts for form validation and actions
- Modular and DRY code with EJS partials

---

## 🗂 Project Structure

```bash
Wanderlust/
│
├── models/               # Mongoose schemas (User, Listing, Review)
├── routes/               # Express routers (users, listings, reviews)
├── controllers/          # Route logic for CRUD operations
├── views/                # EJS templates (partials, pages)
│   ├── listings/
│   ├── users/
│   └── partials/
├── public/               # Static files (CSS, JS, images)
├── utils/                # Mapbox, Cloudinary config, helpers
├── middleware/           # Custom middleware (auth, error handling)
├── .env                  # Environment variables
├── app.js                # Express app entry point
└── package.json

PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
💡 Never upload .env to GitHub. Add it to .gitignore.

🧪 How to Run Locally

# 1. Clone the repository
git clone https://github.com/yourusername/wanderlust.git
cd wanderlust

# 2. Install dependencies
npm install

# 3. Setup environment variables
#    Create a `.env` file using the format above

🧠 What I Learned
Building scalable RESTful applications with Express

Handling secure JWT + session-based authentication

Using Cloudinary and Multer for media upload pipelines

Integrating Mapbox for real-time geolocation

Writing DRY, modular, production-level backend code

👨‍💻 Author
Rydham Cheetu
📧 rydhamcheetu4@gmail.com
🔗 LinkedIn | GitHub
