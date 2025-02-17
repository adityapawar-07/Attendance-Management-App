# AttendanceApp

AttendanceApp is a web-based application designed for faculty to manage student attendance for a specific course. It allows instructors to easily mark attendance, send emails to students who have less attendance than the required criteria, and download the details of all students' attendance.

## Features

- **Mark Attendance**: Easily mark student attendance for each class.
- **Email Notifications**: Send emails to students who have attendance lower than the required threshold.
- **Attendance Report**: Download and view attendance details for all students.
- **Real-time Operations**: Uses AJAX for smooth, real-time updates without page reloads.

## Technologies Used

- **Frontend**:
  - HTML
  - CSS
  - JavaScript
  - jQuery
  - Bootstrap
  
- **Backend**:
  - PHP (XAMPP Server)

- **Database**:
  - MySQL

- **Real-time Operations**:
  - AJAX

## Setup and Installation

### Prerequisites

- Install [XAMPP](https://www.apachefriends.org/index.html) (for running PHP and MySQL).
- Ensure you have a web browser (Google Chrome, Mozilla Firefox, etc.).

### Steps to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/adityapawar-07/AttendanceApp.git
    ```

2. Place the project folder in the `htdocs` directory of your XAMPP installation:
    - For example, move the folder to: `C:\xampp\htdocs\AttendanceApp`

3. Open XAMPP and start the **Apache** and **MySQL** servers.

4. Import the database:
    - Open phpMyAdmin (http://localhost/phpmyadmin).
    - Create a new database named `attendance_app`.
    - Import the `attendance_app.sql` file found in the `sql` folder of this repository.

5. Access the app through your browser:
    ```bash
    http://localhost/AttendanceApp
    ```

## Usage

- **Login**: Login with your faculty account to mark attendance.
- **Attendance Marking**: Select a course and mark student attendance.
- **Email Notifications**: Students with low attendance will receive an email notification.
- **Download Reports**: Download student attendance details as a CSV file.
