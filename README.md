Face Detection - Registration and Login System
This project is a Face Recognition Registration and Login System developed using Django and OpenCV. It allows users to register their faces as a form of authentication and then use facial recognition to log in to the system.

Features
User Registration: Users can register their faces by capturing images using the webcam. The captured images are used to create a face encoding that is stored in the database for future recognition.

Face Login: Registered users can log in to the system using facial recognition. The system captures the user's face and compares it with the stored face encodings to authenticate and grant access.

User Management: The system provides an admin interface where administrators can manage user accounts, view registered faces, and perform CRUD (Create, Read, Update, Delete) operations on user records.

Prerequisites
Before running this project, ensure that you have the following dependencies installed:

Python 
Django 
OpenCV 
face_recognition 

Usage

1)Registering a Face:

Navigate to the registration page by clicking on the "Register" link on the homepage.
Follow the instructions to capture multiple images of your face using the webcam.
Provide a username and password to complete the registration process.
2)Logging in with Face Recognition:

On the homepage, click on the "Login" link.
Allow the system to access your webcam and position your face in front of the camera.
The system will capture your face and compare it with the registered faces to authenticate you.
3)Admin Interface:

To access the admin interface, go to http://127.0.0.1:8000/admin.
Login with superuser credentials (create a superuser using python manage.py createsuperuser if not done already).
Use the admin interface to manage user accounts, view registered faces, and perform CRUD operations on user records.
