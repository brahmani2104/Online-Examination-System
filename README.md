# Online Examination System

## Overview
The Online Examination System is a web-based platform developed to conduct exams remotely. It provides a secure and efficient way to administer tests, manage question banks, and generate instant results. This system offers flexibility and convenience for both students and educators, ensuring a smooth examination process.

## Introduction
In the era of digital education, the need for online examination systems has become paramount. This project aims to provide a comprehensive solution for conducting exams online, eliminating the need for traditional pen-and-paper methods. By leveraging the power of technology, this system streamlines the examination process and enhances the overall experience for all stakeholders involved.

## Existing System
The traditional method of conducting exams involves a lot of manual effort and paperwork. It is time-consuming, prone to errors, and lacks the flexibility required for modern educational practices. Additionally, it requires physical presence, which can be challenging, especially during unforeseen circumstances like the current pandemic.

## Proposed System
The proposed Online Examination System addresses these challenges by providing a secure, efficient, and user-friendly platform for conducting exams online. It allows administrators to create and manage exams, set question papers, and monitor exam progress in real-time. Students can take exams from anywhere, at any time, using their devices, ensuring a convenient and flexible exam experience.

## Tools Used
- Python
- Django
- HTML/CSS
- JavaScript
- MySQL

## Methodology
1. **Requirements Gathering**: Understand the needs and expectations of users.
2. **Design**: Create a user-friendly interface and database schema.
3. **Development**: Implement the system using Django framework and other technologies.
4. **Testing**: Ensure the system meets the requirements and is bug-free.
5. **Deployment**: Deploy the system on a web server for public access.

## Running the Project
### Using `python manage.py runserver`
1. Clone the repository: `git clone https://github.com/your-username/online-examination-system.git`
2. Navigate to the project directory: `cd online-examination-system`
3. Run the Django development server: `python manage.py runserver`
4. Access the application in your web browser at `http://127.0.0.1:8000/`

### Using WampServer for Database
1. Install WampServer from the official website: https://www.wampserver.com/en/
2. Start WampServer and ensure the MySQL service is running.
3. Create a new database for the project using phpMyAdmin.
4. Update the database settings in the Django project's settings file (`settings.py`) to use the MySQL database.
5. Run the Django development server as mentioned above to start the application.
