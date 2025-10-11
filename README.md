# Logbook System

A React-based logbook management system for students and supervisors.

## Features

- **Login Page**: Authentication interface for users
- **Student Dashboard**: View progress, supervision status, and logbook access
- **Supervisor Selection**: Browse and select supervisors
- **Supervisor Dashboard**: Review and supervise student entries
- **New Student Entry**: View student logbook entries by week

## Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

The application will open at `http://localhost:3000`

## Navigation Flow

1. **Login** (`/login`) → Student Dashboard
2. **Student Dashboard** (`/student-dashboard`) → Supervisor Selection or Sign Out
3. **Supervisor Selection** (`/supervisor-selection`) → Back to Student Dashboard
4. **Supervisor Dashboard** (`/supervisor-dashboard`) → New Student Entry or Logout
5. **New Student Entry** (`/new-student-entry`) → Back to Supervisor Dashboard

## Pages

- `/login` - Login page
- `/student-dashboard` - Student dashboard with progress and supervision status
- `/supervisor-selection` - Select a supervisor from available users
- `/supervisor-dashboard` - Supervisor's view of students
- `/new-student-entry` - View student's logbook entries

## Technologies Used

- React 18
- React Router DOM 6
- Lucide React (icons)
- CSS3
