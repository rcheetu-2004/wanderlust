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

```
wanderlust/
├── controllers/       # Route logic for CRUD operations
├── models/            # Mongoose models (User, Campground, Review)
├── routes/            # Express routers for users, listings, reviews
├── views/             # EJS templates (partials, pages)
│   ├── listings/
│   ├── users/
│   └── partials/
├── public/            # Static files (CSS, JS, images)
├── utils/             # Mapbox, Cloudinary config, helpers
├── middleware/        # Custom middleware (auth, error handling)
├── .env               # Environment variables
├── app.js             # Express app entry point
└── package.json
```

---

## 🌐 Environment Variables

Create a `.env` file in the root directory and add the following:

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
MAPBOX_TOKEN=your_mapbox_token
```

---

## 📦 Installation

Follow these steps:

```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust
npm install
```

---

## 📞 Contact

[![Email](https://img.shields.io/badge/Email-rydhamcheetu4@gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rydhamcheetu4@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rydham_Cheetu-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rydhamcheetu)  
[![GitHub](https://img.shields.io/badge/GitHub-rydhamcheetu-333?style=for-the-badge&logo=github)](https://github.com/rydhamcheetu)

> Feel free to reach out for collaborations, suggestions, or queries related to this project.
