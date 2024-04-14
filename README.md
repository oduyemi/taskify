# Taskify Documentation

## Introduction
Taskify is a web application designed for managing and assigning tasks to mentees on an individual basis. It provides a user-friendly interface for mentors to create tasks, assign them to specific mentees, and monitor their progress. Taskify utilizes modern web technologies, including React for building dynamic user interfaces, Tailwind CSS for styling, Material-UI (MUI) for UI components, and interacts with the ProTask API backend.

## Features
- **Task Management**: Mentors can create, edit, and delete tasks.
- **Task Assignment**: Mentors can assign tasks to specific mentees.
- **Task Monitoring**: Mentors can track the progress of assigned tasks and provide feedback.
- **User Authentication**: Secure login and authentication system for mentors and mentees.
- **File Attachments**: Mentors and mentees can attach files to tasks for reference or submission.
- **SMS Verification**: Integration with Twilio for SMS verification during registration and login.

## Tech Stack
- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for quickly styling web applications.
- **Material-UI (MUI)**: A popular React UI framework providing pre-designed components.
- **ProTask API**: Backend built using Node.js, Express.js, and MongoDB, providing the core functionality for task management and user authentication.
- **Twilio**: A cloud communications platform for sending SMS messages.

## Getting Started
To run Taskify locally, follow these steps:
1. Clone the Taskify repository from GitHub.
2. Navigate to the project directory.
3. Install dependencies using npm or yarn: `npm install` or `yarn install`.
4. Start the development server: `npm start` or `yarn start`.
5. Access the Taskify application in your web browser at `http://localhost:3000`.

## Project Structure

```
taskify/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── assets/
│   │   └── ...
│   ├── components/
│   │   ├── TaskList.jsx
│   │   ├── TaskItem.jsx
│   │   ├── LoginForm.jsx
│   │   ├── RegisterForm.jsx
│   │   └── ...
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Register.js
│   │   └── Dashboard.js
│   ├── navigation/
│   │   └── index.js
│   ├── services/
│   │   ├── AuthService.js
│   │   ├── TaskService.js
│   │   └── ...
│   ├── App.js
│   ├── index.js
│   └── ...
└── package.json
```

## Components
- **TaskList**: Displays a list of tasks with options for editing and deleting.
- **TaskItem**: Represents an individual task item with details such as name, description, and assigned mentee.
- **Dashboard**: Main page displaying task lists and options for task management.
- **Login**: Login page for mentors and mentees to authenticate.

## Services
- **AuthService**: Handles user authentication, including login and registration.
- **TaskService**: Manages tasks, including creation, deletion, and assignment.

## External APIs
- **ProTask API**: Backend API for managing tasks and user authentication.
- **Twilio API**: Integration for sending SMS verification codes during registration and login.

## Dependencies
- **react**: Core library for building user interfaces in Taskify.
- **react-router-dom**: Library for managing routes and navigation within the application.
- **axios**: HTTP client for making API requests to the ProTask backend.
- **tailwindcss**: CSS framework for styling Taskify components.
- **@mui/material**: Material-UI library for React components.

## Conclusion
Taskify provides a comprehensive solution for managing mentor-mentee relationships and task assignments. With its intuitive user interface and robust functionality, Taskify streamlines the task management process and enhances collaboration between mentors and mentees. By leveraging modern web technologies and external APIs, Taskify delivers a seamless user experience and empowers mentors to effectively mentor their mentees.
