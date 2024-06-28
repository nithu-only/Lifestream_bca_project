# LifeStream

## Overview
This project is a web application designed to connect blood donors with seekers. It is developed using HTML and CSS for the frontend, PHP for the backend, and MySQL for the database. The development environment includes XAMPP, which provides an easy-to-use interface for managing the Apache server, MySQL, PHP, and Perl.

## Features
- User Registration and Authentication
- Donor and Seeker Matching
- Search Functionality for Blood Types and Locations
- Responsive Design
- Interactive UI

## Technologies Used
- HTML
- CSS
- PHP
- MySQL
- XAMPP

## Installation

### Prerequisites
- XAMPP installed on your machine
- A web browser (e.g., Google Chrome, Mozilla Firefox)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Set Up XAMPP**
   - Download and install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).
   - Start the Apache and MySQL modules from the XAMPP control panel.

3. **Import the Database**
   - Open your web browser and go to `http://localhost/phpmyadmin`.
   - Create a new database named `blood_donor_seeker`.
   - Import the provided SQL file (`database.sql`) into the new database.

4. **Configure the Database Connection**
   - Open the `config.php` file in the project directory.
   - Set the database host, username, password, and database name.
   ```php
   $dbHost = 'localhost';
   $dbUsername = 'root';
   $dbPassword = '';
   $dbName = 'blood_donor_seeker';
   ```

5. **Move Project Files**
   - Move the cloned project files to the `htdocs` directory inside your XAMPP installation folder (e.g., `C:\xampp\htdocs` on Windows).

6. **Access the Application**
   - Open your web browser and go to `http://localhost/your-project-folder`.

## Usage
- Register as a blood donor or seeker.
- Use the search functionality to find blood donors or seekers based on blood type and location.
- Manage your profile and contact potential matches.

## Acknowledgements
- [XAMPP](https://www.apachefriends.org/index.html)
- [PHP](https://www.php.net/)
- [MySQL](https://www.mysql.com/)
