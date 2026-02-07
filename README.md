# Portfolio Server (Backend)

Backend API for a Full-Stack Personal Portfolio website.

This server handles authentication, content management, and data storage for skills, projects, and personal information displayed on the portfolio.

---

## 🚀 Tech Stack

- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **TypeScript** - Typed superset of JavaScript
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT Authentication** - Secure token-based authentication
- **Bcrypt** - Password hashing library
- **Cloudinary** - Cloud-based image storage and management

---

## 📁 Project Structure

```
src/
├── config/       # Database & environment configuration
├── controllers/  # Request handlers for business logic
├── middlewares/  # Authentication & error handling middleware
├── models/       # Mongoose schemas for database
├── routes/       # API route definitions
├── utils/        # Helper functions & utilities
└── app.ts        # Application entry point
```

---

## 🔐 Authentication

- **Admin-only access** - Restricted endpoints for authenticated users only
- **JWT-based authentication** - Token-based user sessions
- **Protected routes** - Middleware-based route protection
- **Secure password handling** - Bcrypt encryption for sensitive data

---

## 📦 API Endpoints

### Authentication Endpoints
- `POST /api/auth/login` - Admin user login

### Skills Endpoints
- `GET /api/skills` - Retrieve all skills
- `POST /api/skills` - Create a new skill
- `PUT /api/skills/:id` - Update existing skill
- `DELETE /api/skills/:id` - Delete skill

### Projects Endpoints
- `GET /api/projects` - Retrieve all projects
- `POST /api/projects` - Create a new project
- `PUT /api/projects/:id` - Update existing project
- `DELETE /api/projects/:id` - Delete project

---

## 🗄️ Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
# Server Configuration
PORT=5000

# Database Configuration
MONGO_URI=your_mongodb_connection_string

# JWT Configuration
JWT_SECRET=your_secret_key_for_jwt

# Cloudinary Configuration
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

## ▶️ Running the Server

### Installation
```bash
npm install
```

### Development Mode
```bash
npm run dev
```

### Production Build
```bash
npm run build
npm start
```

The server will run on: **http://localhost:5000**

---

## 📌 Notes

- ✅ Backend is deployed separately from the frontend for scalability
- ✅ Built following REST API best practices and conventions
- ✅ Designed for scalability, maintainability, and performance
- ✅ Implements security best practices for data protection
- ✅ Type-safe development with full TypeScript support

---

## 🛠️ Built With

This project demonstrates modern backend development practices with focus on security, performance, and maintainability.

---


## Author Information
- **Name:** Abo Al Magd
- **GitHub:** [abo-al-magd-404](https://github.com/abo-al-magd-404)
- **Email:** [abo.al.magd.404@gmail.com](mailto:abo.al.magd.404@gmail.com)
