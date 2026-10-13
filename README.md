# VedacureMe — Hospital Management System

A full-stack healthcare management platform designed to organize patient information, doctor records, appointments, and administrative operations in one centralized application.

## About the Project

VedacureMe streamlines hospital workflows by providing dedicated access for administrators, doctors, and patients. It focuses on organized record management, appointment coordination, and role-based access to healthcare services.

Like a CRM, the platform centralizes important records and interactions, helping users manage information efficiently and maintain organized workflows.

## Key Features

- **Role-Based Authentication:** Separate access for Admin, Doctor, and Patient users.
- **Patient Management:** Organize and manage patient records.
- **Doctor Management:** Maintain doctor information and records.
- **Appointment Management:** Book and manage patient appointments.
- **Doctor Search:** Help patients find available doctors.
- **Centralized Records:** Keep healthcare-related information organized.
- **Administrative Dashboard:** Support hospital administration and management activities.

## Technology Stack

### Frontend
- React.js
- JavaScript
- Vite

### Backend
- Node.js
- Express.js
- REST APIs

### Database
- MongoDB
- Mongoose

## Project Structure

```text
Task-2-Mini-CRM/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md
```

## Getting Started

1. Clone the repository.
2. Install the backend dependencies inside the `backend` directory.
3. Configure your local environment variables.
4. Start the backend server.
5. Install the frontend dependencies inside the `frontend` directory.
6. Start the frontend development server.

Refer to the project configuration files for the exact commands and environment variables.

## Security

- Keep database credentials and secret keys in local environment files.
- Never commit `.env` files or `node_modules` to a public repository.
- Use authenticated and authorized access for protected operations.

## Project Purpose

VedacureMe demonstrates full-stack development concepts, including authentication, role-based access, database integration, REST APIs, and record management.

**Internship:** Future Interns — Full Stack Web Development  
**Project:** VedacureMe Hospital Management System

## Author

Rohit Yadav
