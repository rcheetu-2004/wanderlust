# 🌍 Wanderlust – Travel Listing Web Application

Wanderlust is a full-stack travel platform where users can explore, list, and manage accommodations securely. Built using the MERN stack with Mapbox for maps and Cloudinary for image hosting.

![Backend](https://img.shields.io/badge/Backend-Node.js-informational?style=flat&logo=node.js&logoColor=white&color=339933)
![Framework](https://img.shields.io/badge/Express.js-Backend-blue.svg?logo=express)
![Database](https://img.shields.io/badge/Database-MongoDB-brightgreen.svg?logo=mongodb)
![Auth](https://img.shields.io/badge/Auth-JWT%20%7C%20Bcrypt-yellow.svg)
![Cloud](https://img.shields.io/badge/Cloudinary-Image%20Hosting-blueviolet?logo=cloudinary)
![Map](https://img.shields.io/badge/Mapbox-Map-005eff?logo=mapbox)

---

## 🧠 Features

- 🔐 User authentication with session management
- 🏕️ Campground listing (CRUD)
- 🌍 Map integration (Mapbox)
- 🖼️ Image upload (Cloudinary)
- 💬 Reviews & average ratings
- 🛡️ Secure headers, validation, and sanitization

---

## 🛠 Tech Stack

| Layer       | Tech                            |
|------------|----------------------------------|
| Frontend   | EJS, Bootstrap 5, HTML, CSS      |
| Backend    | Node.js, Express                 |
| Database   | MongoDB, Mongoose                |
| Auth       | Passport.js, Bcrypt              |
| Tools      | Multer, Cloudinary, Mapbox       |
| Security   | Helmet, CSURF, express-validator |

---

## 📂 Project Structure

wanderlust/
├── controllers/ # Route logic for CRUD operations
├── models/ # Mongoose models (User, Campground, Review)
├── routes/ # Express routers for users, listings, reviews
├── views/ # EJS templates (partials, pages)
│ ├── listings/
│ ├── users/
│ └── partials/
├── public/ # Static files (CSS, JS, images)
├── utils/ # Mapbox, Cloudinary config, helpers
├── middleware/ # Custom middleware (auth, error handling)
├── .env # Environment variables
├── app.js # Express app entry point
└── package.json


---

## 🌐 Environment Variables (`.env` Setup)

Create a `.env` file in the root and add:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
MAPBOX_TOKEN=your_mapbox_token

## 📥 Installation Steps

# 1. Clone the repository
git clone https://github.com/your-username/wanderlust.git
cd wanderlust

# 2. Install dependencies
npm install

# 3. Create a .env file
cp .env.example .env

# 4. Fill in your environment variables (see below)

# 5. Start MongoDB (if not running)
mongod

# 6. Run the app
npm run dev

