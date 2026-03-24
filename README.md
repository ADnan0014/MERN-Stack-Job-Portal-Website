# MERN Stack Job Portal Website

This is a **Full Stack Job Portal** website built using **MERN Stack (MongoDB, Express, React, Node.js)**. It allows users (students/job seekers) to browse and apply for jobs and recruiters/admins to post jobs, manage companies, and view applicants.  

---

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Project Structure](#project-structure)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [API Endpoints](#api-endpoints)  
- [Frontend Pages](#frontend-pages)  
- [Screenshots](#screenshots)  
- [License](#license)  

---

## Features

**For Students / Job Seekers:**
- Register and login
- Browse jobs
- Apply for jobs
- View applied jobs and their statuses
- Update profile and upload resume  

**For Recruiters / Admins:**
- Register and login
- Create companies
- Update company details
- Post jobs
- View all applicants for a job
- Update applicant status (accepted/rejected)

---

## Technologies Used

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cloudinary (for profile photos and resumes)
- Multer (file upload handling)
- dotenv (environment variables)  

**Frontend:**
- React.js
- Tailwind CSS
- Redux Toolkit (state management)
- React Router DOM
- Sonner (notifications)

---

## Project Structure

### Frontend (`frontend` folder)

# MERN Stack Job Portal Website

![Project Banner](https://via.placeholder.com/800x200?text=Full+Stack+Job+Portal)

This is a **Full Stack Job Portal** website built using **MERN Stack (MongoDB, Express, React, Node.js)**. It allows users (students/job seekers) to browse and apply for jobs and recruiters/admins to post jobs, manage companies, and view applicants.  

---

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Project Structure](#project-structure)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [API Endpoints](#api-endpoints)  
- [Frontend Pages](#frontend-pages)  
- [Screenshots](#screenshots)  
- [License](#license)  

---

## Features

**For Students / Job Seekers:**
- Register and login
- Browse jobs
- Apply for jobs
- View applied jobs and their statuses
- Update profile and upload resume  

**For Recruiters / Admins:**
- Register and login
- Create companies
- Update company details
- Post jobs
- View all applicants for a job
- Update applicant status (accepted/rejected)

---

## Technologies Used

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cloudinary (for profile photos and resumes)
- Multer (file upload handling)
- dotenv (environment variables)  

**Frontend:**
- React.js
- Tailwind CSS
- Redux Toolkit (state management)
- React Router DOM
- Sonner (notifications)

---

## Project Structure

### Frontend (`frontend` folder)

frontend/
├─ public/
│ └─ index.html
├─ src/
│ ├─ components/ # React Components
│ ├─ redux/ # Redux slices & store
│ ├─ hooks/ # Custom React hooks
│ ├─ lib/ # Utilities
│ ├─ assets/ # Images & logos
│ └─ main.jsx # Entry point
├─ package.json
└─ tailwind.config.js


### Backend (`backend` folder)

backend/
├─ controllers/ # Handles API logic
├─ middlewares/ # Authentication & file upload
├─ models/ # MongoDB Schemas
├─ routes/ # API endpoints
├─ utils/ # DB connection & Cloudinary config
├─ index.js # Server entry point
├─ package.json
└─ .gitignore

---

## Installation & Setup

1. **Clone the repo**  

```bash
git clone https://github.com/ADnan0014/MERN-Stack-Job-Portal-Website.git
cd MERN-Stack-Job-Portal-Website


Backend Setup
cd backend
npm install
Create a .env file inside backend/ folder with:

MONGO_URI=your_mongodb_connection_string
SECRET_KEY=your_jwt_secret
CLOUD_NAME=your_cloudinary_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
PORT=5000

Frontend Setup

cd ../frontend
npm install

Run the Project
Backend:

cd backend
npm run dev

Frontend:
cd frontend
npm run dev

Frontend Pages
Home - Landing page with featured jobs and categories
Jobs - List all jobs with search and filter options
Job Description - Detailed view of a single job
Browse - Search and filter jobs
Profile - User profile with update functionality
Admin Dashboard - Manage companies, jobs, and applicants

License
This project is open-source and free to use.

Notes
Make sure MongoDB is running locally or use a cloud MongoDB instance
Cloudinary is required to store images and resumes
JWT is used for authentication
Tailwind CSS is used for styling

