# JobEase Portal

A full-stack job portal application built using MERN stack (MongoDB, Express, React, Node.js) that allows job seekers to find and apply for jobs, and recruiters to post job openings and manage applications.

## 📋 Features

### For Job Seekers

- User authentication and profile management
- Browse and search job listings
- Filter jobs by various criteria
- Apply for jobs with resume upload
- Track application status
- View application history

### For Recruiters

- Company profile management
- Post and manage job listings
- View applicant profiles
- Review and manage job applications
- Update application status

## 🛠️ Tech Stack

### Frontend

- React.js with Vite
- Redux Toolkit for state management
- TailwindCSS for styling
- Shadcn UI components
- Axios for API calls
- React Router for navigation

### Backend

- Node.js & Express.js
- MongoDB with Mongoose
- JWT for authentication
- Cloudinary for file storage
- Bcrypt for password hashing
- Multer for file handling

## 🔧 Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/1av22/JobEase-Portal.git
cd JobEase-Portal
```

2. Install dependencies for backend

```bash
cd backend
npm install
```

3. Install dependencies for frontend

```bash
cd frontend
npm install
```

4. Create a .env file in the backend directory with the following variables:

```env
PORT=8000
MONGO_URI=your_mongodb_uri
SECRET_KEY=your_jwt_secret_key
CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
```

5. Start the backend server

```bash
cd backend
npm run dev
```

6. Start the frontend development server

```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:5173`

## 📂 Project Structure

```
jobportal-yt/
├── backend/
│   ├── controllers/     # Request handlers
│   ├── middlewares/     # Custom middleware functions
│   ├── models/         # MongoDB models
│   ├── routes/         # API routes
│   ├── utils/          # Helper functions
│   └── index.js        # Entry point
├── frontend/
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── hooks/      # Custom hooks
│   │   ├── redux/      # Redux store and slices
│   │   └── utils/      # Helper functions
│   └── index.html
```
