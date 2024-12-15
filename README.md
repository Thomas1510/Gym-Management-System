# Gym Management System

## Overview

The **Gym Management System** is a web-based application designed to manage various aspects of a gym's operations. Built using **PHP**, **MySQL** (via **XAMPP**), and front-end technologies such as **HTML**, **CSS**, and **JavaScript**, this system offers a simple and efficient solution for managing gym memberships, staff, equipment, and classes. The system provides a user-friendly interface for both gym administrators and members, streamlining the day-to-day activities of a gym.

## Technologies Used

- **PHP**: Used for server-side scripting to handle requests and interact with the database.
- **MySQL**: The database management system used to store and manage data such as member details, membership plans, and workout schedules.
- **XAMPP**: A cross-platform development environment that includes Apache, MySQL, and PHP, used to set up the local server for the application.
- **HTML/CSS**: Used for creating the structure and styling of the web pages.
- **JavaScript**: Provides dynamic functionality and interactivity for the user interface.
- **Bootstrap**: Used for responsive web design to ensure the system works seamlessly across devices.

## Features

- **Member Management**: Administrators can add, update, and remove members, as well as view their membership status and payment history.
- **Membership Plans**: Various membership plans (monthly, yearly) are available for members to choose from, and payment details are recorded.
- **Workout Schedules**: Gym instructors can manage workout schedules, assign classes to members, and track attendance.
- **Staff Management**: Administrators can manage gym staff, including trainers, receptionists, and other personnel.
- **Equipment Tracking**: The system allows administrators to keep track of gym equipment, their condition, and maintenance schedules.
- **Admin Dashboard**: Provides an overview of key data, including active memberships, upcoming classes, and staff management tools.
- **Member Dashboard**: Allows gym members to view their membership details, upcoming classes, and payment history.

## Database Structure

The database for the Gym Management System is built using **MySQL** and managed through **phpMyAdmin** (included with XAMPP). The key tables in the database include:

- **members**: Stores details about gym members such as name, membership type, and payment status.
- **staff**: Stores information about the gym staff, including their roles and schedules.
- **membership_plans**: Contains the different types of membership plans available.
- **workout_classes**: Tracks gym classes, schedules, and attendance.
- **payments**: Manages payment transactions made by gym members.
- **equipment**: Keeps track of gym equipment, including its status and maintenance logs.

## Setup and Installation

### Prerequisites

- **XAMPP**: Ensure that XAMPP (Apache, MySQL, PHP) is installed on your local machine to run the server.
- **PHP 7.x or higher**: The application is built to run on PHP 7.x or above.
- **MySQL Database**: A MySQL database must be configured in XAMPP to store system data.

### Steps to Install

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/gym-management-system.git
    ```

2. Move the project folder to the `htdocs` directory in your XAMPP installation folder (typically found in `C:/xampp/htdocs/` for Windows users).

3. Open **XAMPP** and start the **Apache** and **MySQL** services.

4. Create a new database in **phpMyAdmin** for the system:

    - Open phpMyAdmin (`http://localhost/phpmyadmin/`).
    - Create a new database (e.g., `gym_management`).
    - Import the provided SQL file (`gym_management.sql`) to set up the necessary tables.

5. Configure the database connection settings in the PHP scripts:

    - Open the `config.php` file.
    - Update the database connection details (username, password, database name) according to your local setup.

6. Once everything is set up, open your browser and navigate to:

    ```bash
    http://localhost/gym-management-system/
    ```

    You should now see the Gym Management System home page, where you can log in as an admin or a member.

## Usage

- **Admin Dashboard**: Log in with the admin credentials to manage members, staff, and equipment, and view reports.
- **Member Dashboard**: Members can log in to view their membership information, schedule, and make payments.

---
