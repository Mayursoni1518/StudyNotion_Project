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


### Getting Started
-- **Prerequisites** :
Node.js (v14 or higher)
MongoDB
npm or yarn
Installation
Clone the repository
git clone https://github.com/RaviP9973/studynotion.git
cd studynotion
Install dependencies for both frontend and backend
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../src
npm install
Set up environment variables Create a .env file in the server directory with the following variables:
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
Start the development servers
# Start the backend server
cd server
npm run dev

# Start the frontend server (in a new terminal)
cd src
npm start
Access the application at http://localhost:3000
Project Structure
studynotion/
├── server/                 # Backend code
│   ├── config/             # Configuration files
│   ├── controllers/        # Request handlers
│   ├── middleware/         # Custom middleware
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   └── index.js            # Server entry point
│
├── src/                    # Frontend code
│   ├── components/         # React components
│   ├── pages/              # Page components
│   ├── services/           # API services
│   ├── slices/             # Redux slices
│   ├── utils/              # Utility functions
│   └── App.js              # Main application component
│
└── README.md               # Project documentation

Authentication Flow
User registers with email and receives OTP
OTP verification completes registration
User logs in with email and password
JWT token is generated and stored in cookies and localStorage
Token is used for authenticated API requests
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
DiceBear for avatar generation
Cloudinary for media storage
MongoDB for database services
