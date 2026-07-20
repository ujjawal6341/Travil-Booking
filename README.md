# Travelers

## Overview

Travelers is a full-stack travel web application designed to help users explore destinations, plan trips, and manage their travel experiences through an intuitive and responsive interface.

The project is built using the MERN ecosystem, with a stronger emphasis on backend development, focusing on RESTful APIs, authentication, database design, and efficient data management.

---

## Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6+)
* Axios
* React Router

### Backend

* Node.js
* Express.js
* JWT Authentication
* bcrypt.js

### Database

* MongoDB
* Mongoose ODM

### Tools & Utilities

* Git & GitHub
* Postman
* VS Code
* Nodemon
* dotenv

---

## Features

### User Features

* User Registration and Login
* JWT-based Authentication
* Browse Travel Destinations
* Search and Filter Locations
* View Destination Details
* Create and Manage Travel Plans
* Responsive User Interface
* Profile Management

### Admin Features

* Add, Edit, and Delete Destinations
* Manage Users
* Monitor Platform Activities
* Dashboard Analytics

---

## Project Structure

```bash
Travelers/
│
├── client/                 # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── services/
│       └── App.js
│
├── server/                 # Node.js Backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── app.js
│   └── server.js
│
├── .env
├── package.json
└── README.md
```

---

## Backend Highlights

This project is primarily backend-focused and demonstrates:

* REST API Development
* MongoDB Schema Design
* Authentication & Authorization
* Middleware Implementation
* Error Handling
* Environment Variable Management
* Secure Password Hashing
* API Testing with Postman
* Modular Code Architecture

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/travelers.git
cd travelers
```

### Install Dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd server
npm install
```

---

## Environment Variables

Create a `.env` file in the `server` directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## Running the Application

### Start Backend Server

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

The application will run on:

* Frontend: `http://localhost:3000`
* Backend: `http://localhost:5000`

---

## API Endpoints

### Authentication

| Method | Endpoint             | Description   |
| ------ | -------------------- | ------------- |
| POST   | `/api/auth/register` | Register User |
| POST   | `/api/auth/login`    | Login User    |

### Users

| Method | Endpoint             | Description      |
| ------ | -------------------- | ---------------- |
| GET    | `/api/users/profile` | Get User Profile |
| PUT    | `/api/users/profile` | Update Profile   |

### Destinations

| Method | Endpoint                | Description             |
| ------ | ----------------------- | ----------------------- |
| GET    | `/api/destinations`     | Get All Destinations    |
| GET    | `/api/destinations/:id` | Get Destination Details |
| POST   | `/api/destinations`     | Add Destination         |
| PUT    | `/api/destinations/:id` | Update Destination      |
| DELETE | `/api/destinations/:id` | Delete Destination      |

---

## Database Models

### User

* Name
* Email
* Password
* Profile Image
* Created At

### Destination

* Title
* Description
* Location
* Price
* Images
* Rating

### Travel Plan

* User ID
* Destination ID
* Travel Date
* Status

---

## Learning Outcomes

Through this project, I gained experience in:

* Building scalable backend applications using Node.js and Express.js.
* Designing MongoDB schemas with Mongoose.
* Implementing JWT authentication and authorization.
* Creating and testing REST APIs.
* Managing application state and frontend-backend communication.
* Following industry-standard project structure and best practices.

---

## Future Enhancements

* Google Maps Integration
* Payment Gateway Integration
* Booking System
* Email Notifications
* Role-Based Access Control
* Docker Deployment
* Cloud Hosting (AWS)

---

## Author

**Ujjawal Bhardwaj**

* IIT Madras BS Degree in Data Science and Applications
* Backend Developer
* Cybersecurity Enthusiast
* Security Researcher

---

## License

This project is licensed under the MIT License.

---

### If you found this project useful, consider giving it a star on GitHub.
