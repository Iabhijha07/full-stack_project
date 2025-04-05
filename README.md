## Overview
Intern Management System
The Intern Management System is a web-based platform designed to streamline the management of interns in an organization. It allows administrators, mentors, and interns to efficiently manage tasks, track progress, and improve communication.

## Project Features
- User Roles & Authentication :
  Admin:- Manages interns, mentors, and tasks.
  Mentor:- Oversees assigned interns, reviews progress, and provides feedback.
  Intern:- Views assigned tasks, submits progress, and receives feedback.
  Authentication:- JWT-based authentication for secure access.
- Intern Management :
  Add, update, or remove interns.
  Assign interns to mentors.
  Track attendance and performance.
- Task & Project Management :
  Assign tasks to interns.
  Track task status (Pending, In Progress, Completed).
  Allow interns to submit progress updates.
- Performance Tracking & Reports :
  Generate performance reports.
  Track internship progress via dashboards.
  Mentor feedback system.
- Communication & Notifications :
  Interns receive notifications for assigned tasks and deadlines.
  Mentors get updates when interns submit work.
  Email notifications for important updates.

## Key Technologies
- Frontend :
  React.js (for dynamic UI)
  Tailwind CSS / Bootstrap (for styling)
  Redux (for state management)
- Backend :
  Node.js + Express.js (for handling requests)
  MongoDB (for storing user data, tasks, and reports)
- Authentication & Security :
  JWT (JSON Web Tokens) for authentication
  Bcrypt.js for password hashing
  Role-based access control

## How To Run The Project
Clone the Repository :
      
    git clone https://github.com/your-username/intern-management-system.git
    cd intern-management-system

 Install the required dependencies :
 - Backend Setup

       cd backend
       npm install
 - Frontend Setup

       cd frontend
       npm install
 - Environment Variables (.env)

       PORT=5000
       MONGO_URI=your_mongodb_connection_string
       JWT_SECRET=your_secret_key

 - Start the Application
 - Start Backend

       npm run dev
 - Start Frontend

       npm start



   
   

   

   

   
 





