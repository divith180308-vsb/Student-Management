# Student-Management

1. Project Overview

The Student Management System is a full-stack CRUD web application developed to manage student records digitally. It allows users to add, view, update, delete, search, and filter student information through a simple and responsive interface.

2. Objectives
Manage student records efficiently.
Implement Create, Read, Update, and Delete operations.
Connect frontend, backend, REST API, and database.
Apply input validation and error handling.
Test the application using Postman.
3. Technology Stack
Component	Technology
Frontend	React, JavaScript, CSS
Backend	Django + Django REST Framework
Database	SQLite
API Testing	Postman
Version Control	Git/GitHub
4. Student Details

The system stores:

Student ID
Name
Roll Number
Email
Department
Year
Phone Number
5. Main Features
Add new student records.
Display all student records.
Edit and update student details.
Delete student records with confirmation.
Search and filter students.
Client-side and server-side validation.
Prevent duplicate roll numbers and emails.
Display success and error messages.
Responsive user interface.
6. CRUD Operations
Operation	Description
Create	Add a new student
Read	View student records
Update	Modify existing details
Delete	Remove a student
7. REST API
Method	Endpoint	Purpose
POST	/api/students/	Create
GET	/api/students/	Read all
GET	/api/students/{id}/	Read one
PUT/PATCH	/api/students/{id}/	Update
DELETE	/api/students/{id}/	Delete
8. System Architecture
User
  ↓
React Frontend
  ↓
REST API
  ↓
Django REST Framework
  ↓
SQLite Database
9. Validation

The application validates required fields, email format, phone number, academic year, and unique roll number/email. Invalid inputs are handled with clear error messages.

10. Setup
Backend
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
Frontend
cd frontend
npm install
npm run dev

Run the backend and frontend together to use the complete application.

11. Testing

The application is tested for:

Create, Read, Update and Delete
Valid and invalid inputs
Duplicate records
Invalid student IDs
Search and filtering
API responses
Database persistence

Postman is used to test the REST API endpoints.

12. Git/GitHub

Git is used for source-code management and regular commits. The final project can be pushed to a GitHub repository for submission.

13. Future Enhancements
Student authentication
Attendance management
Marks and results management
Export reports to PDF/CSV
MySQL/PostgreSQL integration
Admin dashboard
14. Conclusion

The Student Management System demonstrates a complete full-stack CRUD application using React, Django REST Framework, REST API, and SQLite, fulfilling the major requirements of the CRUD Web Application Development activity.
