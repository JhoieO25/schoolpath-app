# SchoolPath App

**SchoolPath** is a modern, mobile-first school management system designed to simplify and digitize everyday school operations.  
It bridges the communication gap between **teachers, parents, and administrators** through a unified, easy-to-use platform.

---

## Project Overview

The project was developed as part of a postgraduate computing program to demonstrate advanced software engineering practices.  
It integrates complex server-side logic with a responsive Progressive Web App (PWA) frontend — ensuring accessibility, scalability and ease of use for schools in both urban and rural settings.

**Core Features:**
- **Student Attendance** — teachers can mark and manage daily attendance.  
- **Staff Geo-Clock-In** — staff can clock in only within school premises using geolocation verification.  
- **Student Results Upload** — teachers upload student results; parents can view them securely.  
- **Parent–Support Chat** — real-time messaging for parents to reach out to school administrators.  
- **E-Commerce Section** — shop for schoolwear, stationery, and other supplies.  
- **Role-Based Access** — administrators, teachers, parents and staff each have controlled permissions.

---

## Architecture

The system adopts a **3-tier client–server architecture**, combining a **React Progressive Web App (PWA)** frontend, a **Spring Boot REST API + WebSocket** backend, and a **MySQL** relational database.  
The backend follows a **modular MVC + Service** structure and integrates **Spring Security (JWT)** for authentication and role-based access control.




