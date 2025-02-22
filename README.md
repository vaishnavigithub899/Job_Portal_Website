# Job Portal Website (MERN Stack)

## 📌 Project Overview
This is a **MERN (MongoDB, Express.js, React.js, Node.js)** stack-based web application that allows job seekers to find jobs and employers to post job listings. The system provides user authentication, role-based access control, and a dynamic job search functionality.

## 🚀 Features
- **User Authentication & Authorization** (Clerk-based authentication for Job Seekers and Employers)
- **Job Posting & Approval System**
- **Job Search & Filtering** (By category, location etc.)
- **Resume Upload & Profile Management**
- **Error Tracking & Monitoring** (Integrated with Sentry)
- **Responsive Design** (Works on all devices)

## 🛠️ Tech Stack
### Frontend:
- React.js (Vite)
- Tailwind CSS (Styling)
- React Router DOM (Navigation)
- Axios (API Requests)
- Sentry (Error Tracking & Monitoring)

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Clerk Authentication
- Cloudinary (For resume and profile images upload)
- Sentry (Error Tracking & Monitoring)

## 🔧 Installation & Setup
### Prerequisites:
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/vaishnavigithub899/Job_Portal_Website.git
   cd Job_Portal_Website
   ```

2. **Backend Setup**
   ```sh
   cd server
   npm install
   npm run server  # Starts the backend server
   ```

3. **Frontend Setup**
   ```sh
   cd client
   npm install
   npm run dev  # Runs the frontend
   ```

4. **Environment Variables**
   Create a `.env` file in the backend folder with the following:
   ```env
   MONGO_URI=your_mongodb_uri
   CLERK_SECRET_KEY=your_clerk_secret_key
   CLOUDINARY_URL=your_cloudinary_url
   SENTRY_DSN=your_sentry_dsn
   ```

## 🔄 API Endpoints
| Method | Endpoint               | Description                   |
|--------|------------------------|-------------------------------|
| POST   | `/api/auth/register`   | Register new user             |
| POST   | `/api/auth/login`      | Login user                    |
| GET    | `/api/jobs`            | Get all job listings          |
| POST   | `/api/jobs`            | Post a new job                |
| GET    | `/api/applications`    | Get all job applications      |


## 👨‍💻 Contributor
- [@vaishnavijha](https://github.com/vaishnavigithub899)

## 💬 Feedback
If you have any suggestions or issues, feel free to open an issue in this repository!





