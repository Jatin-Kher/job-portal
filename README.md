# MERN Job Portal

A full-stack Job Portal application built with the MERN stack (MongoDB, Express, React, Node.js) that allows users to search, post, edit, and manage job listings. The project includes user authentication, job filtering, and salary estimation features.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Contact](#contact)

---

## Features

- User authentication (Sign up, Login, Logout) with Firebase
- Post, edit, and delete job listings
- Filter jobs by location, salary, experience, and employment type
- Search jobs by title or keyword
- View detailed job information
- Estimate salaries for various roles
- Responsive UI with Tailwind CSS

---

## Tech Stack

- **Frontend:** React, React Router, Tailwind CSS, React Hook Form, Firebase Auth
- **Backend:** Node.js, Express, MongoDB
- **Other:** SweetAlert2, React Select, Vite

---

## Folder Structure

```
Mern_JobPortal/
├── job-portal-client/   # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── firebase/
│   │   ├── pages/
│   │   ├── router/
│   │   └── ...
│   ├── package.json
│   └── ...
├── job-portal-server/   # Express backend
│   ├── index.js
│   ├── .env
│   ├── package.json
│   └── ...
└── README.md
```

---

## Getting Started

### Backend Setup

1. **Navigate to the backend folder:**
   ```sh
   cd job-portal-server
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Configure environment variables:**
   - Create a `.env` file in `job-portal-server/`:
     ```
     DB_USER=your_mongodb_user
     DB_PASSWORD=your_mongodb_password
     ```

4. **Start the backend server:**
   ```sh
   npm start
   ```
   The server will run on `http://localhost:5000` by default.

---

### Frontend Setup

1. **Navigate to the frontend folder:**
   ```sh
   cd job-portal-client
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the frontend development server:**
   ```sh
   npm run dev
   ```
   The app will be available at `http://localhost:5173` (or as shown in your terminal).

---

## Environment Variables

- **Backend:**  
  Set MongoDB credentials in `job-portal-server/.env`.

- **Frontend:**  
  Firebase configuration is hardcoded in [`src/firebase/firebase.config.js`](job-portal-client/src/firebase/firebase.config.js).  
  For production, consider using environment variables.

---

## Usage

- **Sign Up / Login:**  
  Create an account or log in using your email and password.

- **Browse Jobs:**  
  Use the search bar and sidebar filters to find jobs by title, location, salary, and more.

- **Post a Job:**  
  Authenticated users can post new jobs via the "Post A Job" page.

- **Edit/Delete Jobs:**  
  Manage your posted jobs from the "My Jobs" section.

- **Salary Estimation:**  
  Visit the "Salary estimate" page to view average salaries for various roles.

---

## Contact

For any questions, suggestions, or support, feel free to contact me:

- **Name:** Jatin Kumar  
- **Email:** jatinkher100@gmail.com  
- **LinkedIn:** [https://www.linkedin.com/in/jatin-kumar-a0873a289/](https://www.linkedin.com/in/jatin-kumar-a0873a289/)

---

**Happy Coding!**