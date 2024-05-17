# Cyber Cafe Management System 🖥️

## Overview

The Cyber Cafe Management System is a project developed for our high school final project submission. It was a collaborative effort with my colleagues, aimed at streamlining the operations of a cyber cafe. The system includes features for user management, session tracking, billing, and reporting.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

---

## Introduction

The Cyber Cafe Management System was designed to automate the daily operations of a cyber cafe. It handles user registration, session monitoring, billing calculations, and generates reports. The project was a valuable learning experience, allowing us to apply various programming concepts and work effectively as a team.

---

## Features

- **User Registration**: Allows new users to register and create accounts.
- **Session Management**: Tracks user login and logout times to calculate session duration.
- **Billing System**: Automatically calculates the cost based on session duration.
- **Admin Dashboard**: Provides an interface for administrators to manage users and view reports.
- **Reporting**: Generates daily, weekly, and monthly reports of usage and revenue.

---

## Technologies Used

- **Programming Language**: Python
- **Database**: ![MySQL](https://img.shields.io/badge/MySQL-00000F?style=flate&logo=mysql&logoColor=white)
- **IDE**: ![Vim](https://img.shields.io/badge/-Vim-019733?style=flat&logo=vim&logoColor=white)
- **Libraries**: Internal only (no external libraries used)

---

## Installation

To run the Cyber Cafe Management System on your local machine, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-github-username/Cyber-Cafe-Management-System.git
    cd Cyber-Cafe-Management-System
    ```

2. **Set up the database**:
    - Install MySQL and create a database for the project.
    - Run the provided SQL script to set up the necessary tables:
    ```sh
    mysql -u username -p database_name < database/setup.sql
    ```

3. **Run the program**:
    - Open the project in Vim and run the Python scripts to start the system:
    ```sh
    vim src/main.py
    python src/main.py
    ```

---

## Usage

1. **Admin Login**:
    - Use the default admin credentials to log in to the system.
    - Admin Username: `admin`
    - Admin Password: `password`

2. **User Registration**:
    - Register new users by entering their details in the registration form.
    
3. **Session Management**:
    - Log in users at the start of their session and log them out when they finish.
    - The system will automatically calculate the session duration and corresponding charges.

4. **Billing**:
    - Generate bills for each session based on the duration and predefined rates.

5. **Reporting**:
    - Access various reports from the admin dashboard to monitor usage and revenue.
