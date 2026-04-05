# EduManage - Student Management System

EduManage is a responsive frontend web application for school administration. It helps admins and teachers manage students, courses, and attendance in a clean dashboard interface.

## Live Demo (GitHub Pages)
Visit the project here:

**https://heangsat.github.io/Student_Management_system/**

## Project Overview
This project is a functional frontend prototype built for education management workflows.

### Main modules
- Dashboard overview with quick stats and recent activity
- Student management (list, search/filter, detail, CRUD)
- Student enrollment form
- Course management
- Attendance tracking with CSV export
- Login page with role-based demo access (Admin, Teacher)

## Tech Stack
- HTML5
- CSS3
- Bootstrap 5.3
- Bootstrap Icons
- Vanilla JavaScript (ES6+)
- LocalStorage (client-side persistence)

## Demo Credentials
Use one of these accounts on the login page:

- Admin: `admin@school.edu` / `admin123`
- Teacher: `teacher@school.edu` / `teacher123`

## Project Structure

```text
.
├── index.html
├── pages/
│   ├── login.html
│   ├── student-list.html
│   ├── student-enroll.html
│   ├── student-detail.html
│   ├── course.html
│   └── attendance.html
├── css/
│   ├── style.css
│   └── login.css
├── js/
│   └── main.js
└── PRESENTATION.md
```

## How Data Works
The app uses browser LocalStorage as a lightweight database:
- `eduManage_user` for active session
- `eduManage_remember` for remembered login email
- `eduManage_students` for student records
- `eduManage_courses` for course records
- `eduManage_attendance_v2` for attendance by date

If data does not exist yet, sample students and courses are automatically seeded on first load.

## Run Locally
Because this is a static web project, you can run it directly in your browser:

1. Open `index.html` in a browser, or
2. Use a local static server (recommended)

Example using VS Code Live Server or any static server.

## Future Improvements
- Connect to a backend API and real database
- Add role-based permissions and secure auth
- Add analytics and chart-based reporting
- Add notifications for attendance alerts

## Author
Developed as a student management system frontend prototype.
