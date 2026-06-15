# IntervueX

## Overview
IntervueX is a full-stack web application designed to streamline interview preparation and assessment workflows. It provides an interactive and modern user experience with a React-based frontend and a Node.js backend.

## Features
### User Management
- User Registration & Login
- JWT Authentication
- Protected Routes
- Secure Password Hashing

### Interview Preparation
- Interactive Interview Sessions
- AI-powered assistance
- Resume Analysis
- Coding Environment Integration
- Personalized Feedback

### Analytics & Dashboard
- Performance Tracking
- Visual Reports & Charts
- Progress Monitoring
- Activity Dashboard

### File Management
- Resume Upload
- PDF Parsing
- Cloudinary Storage Integration

## Tech Stack
### Frontend
- React
- Vite
- Tailwind CSS
- Additional libraries: @monaco-editor/react, axios, framer-motion, html2canvas, jspdf, lucide-react, react, react-dom, react-hot-toast, react-router-dom, recharts

### Backend
- Node.js
- Express.js (if used in your server implementation)
- REST APIs

## Project Structure
```
IntervueX/
├── client/
├── server/
├── README.md
└── SETUP.md
```

## Installation
```bash
# Clone repository
git clone <your-github-repo-link>
cd IntervueX

# Install dependencies
cd client
npm install

# In another terminal
cd server
npm install
```

## Run Locally
```bash
# Start frontend
cd client
npm run dev

# Start backend
cd server
npm start
```

## Environment Variables
Create a `.env` file in the required directories and add your project-specific variables.

