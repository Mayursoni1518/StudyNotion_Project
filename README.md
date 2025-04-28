# StudyNotion - Educational Platform

[Live Demo](https://study-notion-frontend-seven-chi.vercel.app/)

StudyNotion is a dynamic educational platform where students can purchase courses, and instructors can create and sell courses. Built with a full-stack architecture, the platform provides a seamless user experience for both learning and teaching.

## Features

### For Students:
- Browse and search for courses across multiple categories.
- Purchase courses with secure payment integration.
- Access purchased courses and track progress.
- User-friendly dashboard for managing enrolled courses.

### For Instructors:
- Create, manage, and upload courses with detailed sections and subsections.
- Track sales and revenue through an intuitive dashboard.
- Engage with students through course content.

### Core Functionality:
- User authentication and role-based access control (student/instructor).
- Responsive and modern UI for all devices.
- Secure backend with efficient database integration.
- Payment gateway integration for smooth transactions.

### How to Set Up and Run the Project
***Clone the repository*** 
 -> git clone https://github.com/RaviP9973/studynotion.git
 -> cd studynotion

### Install backend dependencies
cd server
npm install

## Install frontend dependencies
cd ../src
npm install

### Set up environment variables
Create a .env file inside the server folder with the following variables:
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

## Start the backend server
cd server
npm run dev

## Start the frontend server (open a new terminal)
cd src
npm start

## Access the application at
http://localhost:3000

## Dependencies and Configurations Required
Node.js (v14 or higher)

MongoDB (local or cloud database like MongoDB Atlas)

npm or yarn (for package management)

Cloudinary account (for media storage like images/videos)

# Major Packages Used
Backend:

Express

Mongoose

Bcrypt

JsonWebToken

Cloudinary

dotenv

cookie-parser

nodemailer

Frontend:

React

Redux Toolkit

React Router DOM

Tailwind CSS

Axios

React Toastify

Formik

Stripe (for payment gateway)


