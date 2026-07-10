# House Rent - MERN Stack Application

A full-stack House Rent web application built using the MERN stack. The platform allows users to browse available properties, register/login, book properties, and enables owners/admins to manage property listings.

## Features

* User Registration & Login
* JWT Authentication
* Browse Available Properties
* Filter Properties by Type, Address, and Ad Type
* Property Booking System
* Owner Dashboard
* Admin Dashboard
* Property Image Upload
* Responsive User Interface
* MongoDB Atlas Database

## Tech Stack

### Frontend

* React.js
* React Router
* Bootstrap
* Axios
* Ant Design

### Backend

* Node.js
* Express.js
* JWT Authentication
* Multer

### Database

* MongoDB Atlas
* Mongoose

## Deployment

### Frontend

* Vercel

### Backend

* Render

### Database

* MongoDB Atlas

## Project Structure

```
House-Rent/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── index.js
│
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/karrisribhagyadhaneswarareddy-maker/House-Rent.git
```

### Install Dependencies

Backend

```bash
cd backend
npm install
```

Frontend

```bash
cd frontend
npm install
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
npm start
```

## Environment Variables

Backend (.env)

```
PORT=8001
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Live Demo

Frontend:
https://house-rent-alpha.vercel.app

Backend API:
https://house-rent-backend-r585.onrender.com

## Author
G.Hemanth

GitHub:
https://github.com/karrisribhagyadhaneswarareddy-maker
