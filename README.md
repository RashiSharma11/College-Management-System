
# College Management System

A web-based application designed to manage and streamline various academic and administrative processes within a college. This system facilitates efficient handling of student, staff, and placement records, while also ensuring secure login functionalities and dynamic updates.

## Features

- **Student Management**: Add, update, delete, and search student records.
- **Staff Management**: Manage staff records including addition, updates, and display functionalities.
- **Placement Management**: Store and manage placement-related data.
- **Authentication**: Secure login and logout mechanisms.
- **User Interface**: Includes forms, search functionality, and display sections for better navigation and usability.

## Technologies Used

- **Front-end**: 
  - HTML5
  - CSS3
  - JavaScript

- **Back-end**:
  - PHP

- **Database**:
  - MySQL

## Installation Guide

1. **Clone or Download the Project**:
   - Clone the repository or download the project as a ZIP file.

2. **Server Setup**:
   - Install a local server environment like [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](http://www.wampserver.com/).
   - Place the project folder inside the `htdocs` directory of your local server setup.

3. **Database Setup**:
   - Import the SQL files provided in the `/project` directory:
     - `login.sql`
     - `placement.sql`
     - `studentinfo.sql`
     - `staffinfo.sql`
   - You can use phpMyAdmin to create a new database and import these SQL files.

4. **Configure Database Connection**:
   - Open the `db_conn.php` and `connection.php` files.
   - Update the database credentials (hostname, username, password, database name) based on your local setup.

5. **Run the Project**:
   - Start your local server.
   - Open a browser and navigate to `http://localhost/project/index.php`.
```
project/
│
├── 6 images/                          # Various images for styling and content
├── about.php                          # About page of the system
├── connection.php                     # Database connection setup
├── contact.php                        # Contact form page
├── contact1.php                       # Alternate contact form
├── css.css                            # Main CSS file for styling
├── css1.css                           # Additional CSS for styling
├── database.php                       # Database operations handling
├── db_conn.php                        # Another DB connection file
├── delete.png                         # Delete icon for UI
├── display.css                        # Styling for display pages
├── displaystudent.php                 # Displays student information
├── fetch.php                          # Fetch data from the database
├── form.css                           # Styling for form elements
├── form1.css                          # Additional form styling
├── frmContact1.html                   # Contact form HTML page
├── gallery1.html                      # Image gallery HTML page
├── home.php                           # Homepage of the system
├── icon-256x256.png                   # Icon for UI
├── index.php                          # Main entry point of the system
├── info.php                           # Information page
├── login.php                          # User login page
├── login.sql                          # SQL file for login table schema
├── logout.php                         # Handles user logout
├── new.css                            # Additional stylesheet for new elements
├── place.php                          # Handles place management
├── Placement.PHP                      # Placement-related functionality
├── placement.sql                      # SQL file for placement data
├── placementsearch.php                # Search placements
├── placementupdate.php                # Update placement records
├── scorner.php                        # Staff corner management
├── search.php                         # General search functionality
├── searchstaff.php                    # Search staff records
├── staff.php                          # Manage staff information
├── staffcorner.php                    # Staff corner page
├── staffdeleterecord.php              # Delete staff records
├── staffdisplay.php                   # Display staff information
├── staffinfo.sql                      # SQL schema for staff info
├── staffupdate.php                    # Update staff records
├── student.css                        # Student page styling
├── student.php                        # Manage student records
├── studentdeleterecord.php            # Delete student records
├── studentinfo.sql                    # SQL schema for student info
├── studentsearch.php                  # Search student records
├── style.css                          # Global stylesheet for the project
├── update-process.php                 # Handle update operations
├── updateplacement.php                # Update placement information
├── updatestaff.php                    # Update staff information
├── updatestudent.php                  # Update student information
└── README.md                          # Project README file

```

## How to Use

### Login
1. Use the `login.php` page to access the system. 
2. Upon successful login, the system redirects you to the homepage.

### Student Management
- **Add Student**: Use the provided form to add student information.
- **Update Student**: Search for the student and edit their details.
- **Delete Student**: Remove a student’s record from the system.

### Staff Management
- Similar functionalities as student management (add, update, delete, search).

### Placement Management
- Manage placement data using the dedicated `placement.php` page.
  
## Screenshots

1. **Login Page**
   ![Login Page](assets/login_page.jpg)

2. **Student Management Interface**
   ![Student Management](assets/student_management.jpg)

## Future Enhancements

- Adding an admin role for enhanced privileges.
- Improving the UI with modern CSS frameworks like Bootstrap.
- Integrating a notification system for alerts and reminders.
