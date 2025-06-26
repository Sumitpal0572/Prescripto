# Prescripto - Online Doctor Appointment Booking System

## Overview

Prescripto is a full-stack web application that allows users to book online doctor appointments in real-time. Users can sign up, log in, select a doctor, and schedule appointments. Additionally, doctors and administrators have dedicated dashboards to manage bookings and availability.

## Deployment Link

#### Frontend Deployment Link

[Watch Frontend Live](https://prescripto-alpha-smoky.vercel.app/)

### Backend Deployment Link

(https://prescripto-backend-v265.onrender.com)

## Repository Structure

This project is divided into three separate repositories:

1. **Frontend (Client)** - This repository contains the user interface built with React and Vite.
2. **Backend (API Server)** - The backend is developed using Node.js, Express, and MongoDB.  
   👉 [Visit Backend Repository](https://github.com/Sumitpal0572/prescripto-backend)
3. **Admin Panel** - The admin dashboard for managing doctors and appointments.  
   👉 [Visit Admin Panel Repository](https://github.com/Sumitpal0572/Prescripto_admin)

## Tech Stack

- **Frontend:** React.js (Vite), Tailwind CSS, Cloudinary (for image uploads)
- **Backend:** Node.js, Express.js, MongoDB, JWT Authentication
- **Admin Panel:** React.js (Vite), Tailwind CSS, Role-based authentication

## Features:

**User Features**

- Sign up and log in with authentication (JWT-based).
- Browse and select doctors based on specialty.
- Book appointments based on real-time availability.
- View and manage booked appointments.
- Update profile details, including profile pictures (uploaded via Cloudinary).

**Doctor Panel**

- Log in with credentials.
- View appointments assigned to them.
- Mark appointments as completed or canceled.
- View total income earned from completed appointments.
- Update their availability status.

**Admin Panel**

- Log in with admin credentials.
- View a dashboard displaying appointments for all doctors.
- Add new doctors to the platform.
- Cancel appointments for any doctor.
- Update doctors’ availability status.

## Installation & Setup

- **Frontend:**

1. **Clone the Repository**

```
git clone https://github.com/Sumitpal0572/Prescripto.git
cd frontend
```

2. **Install Dependencies:**

```
npm install
```

3. Create a .env file:

```
VITE_BACKEND_URL= your_backend_url
```

4. Start the Application:

```
npm run dev
```

- **Backend:**

1. **Clone the Repository**

```
git clone https://github.com/Sumitpal0572/backend-prescripto.git
cd backend
```

2. **Install dependencies:**

```
npm install
```

3. Create a .env file:

```
CLOUDINARY_NAME = 'your_cloudinary_name'
CLOUDINARY_API_KEY = 'cloudinary_api_key'
CLOUDINARY_SECRET_KEY = "cloudinary_secret_key"
JWT_SECRET = "jwt_secret"
```

4. Start the Application:

```
node server.js
```

- **Admin Panel:**

1. **Clone the repository**

```
git clone https://github.com/Sumitpal0572/admin-prescripto.git
cd admin
```

2. **Install dependencies:**

```
npm install
```

3. Create a .env file:

```
VITE_BACKEND_URL = 'your_backend_url'
```

4. Start the Application:

```
npm run dev
```
