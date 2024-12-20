# Student-management-System
                                            Student Management Portal
-----------------------------------------------------------------------------------------------------
1. Table of Contents
2. Introduction
3. Features
4. Technologies Used
5. Project Workflow
6. File Structure
7. Future Enhancements

### Introduction:
------------------------------------------------------------------
The Student Management Portal is a web-based application designed to streamline the management of student data,
including registration, course enrollment, profile management, and grade viewing. The portal is built using Flask,
a lightweight Python web framework, and MySQL for database management.

### Features:
----------------------------------------------------------------
1.Student Registration: Allows students to create an account by providing personal details and a profile photo.
2.User Authentication: Secure login and logout functionality using hashed passwords.
3.Profile Management: Students can view and update their profiles, including their name, email, courses, and profile photo.
4.Course Enrollment: Students can enroll in courses and view the courses they have selected.
5.Grade Viewing: Students can view their grades for different subjects in a tabular format.
6.Responsive Design: The portal is designed to be responsive and accessible on various devices.

 ### Technologies Used:
------------------------------------------------------------------
Frontend: HTML, CSS, Bootstrap
Backend: Python, Flask
Database: MySQL
Other Libraries:
Werkzeug for secure file handling
hashlib for password hashing

### Project Workflow
----------------------------------------------------------------
#### The workflow of the project is as follows:
1.User Registration: Users sign up with personal details.
2.Login: Authenticated users can log in to access the portal.
3.Profile Management: Users can view and update their profile information.
4.Course Enrollment: Users select and enroll in courses.
5.Grade Viewing: Users view their grades for enrolled courses.

--------------------------------------------------
student-management-portal/

│

├── app.py                # Main application file

├── config.py             # Database configuration file

├── templates/            # HTML templates

│      ├── index.html

│      ├── register.html

│      ├── login.html

│      ├── profile.html

│      ├── enroll.html

│      └── grades.html

├── static/               # Static files (CSS, images, uploads)

│     ├── css/

│     ├── images/

│     └── uploads/

├── requirements.txt      # Python dependencies

       └── README.md             # Project documentation






### Future Enhancements:
----------------------------------------------------------------------
#### Admin Panel: 
Add an admin interface for managing student data and courses.
#### Email Notifications:
Implement email notifications for course enrollments and grade updates.
#### Reporting:
Add functionality for generating student performance reports.```


















