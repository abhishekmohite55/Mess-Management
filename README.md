# Mess-Management  
Manage user accounts, admin privileges, feedback, and profile data in a secure web application.  

## Overview  
Mess-Management is a PHP web application built with MySQL and Bootstrap that provides user registration, login, feedback submission, and role-based dashboards. It supports both standard users and administrators for account management and system oversight.  

## Features  
- User registration and secure login system  
- Feedback submission with rating system  
- Profile editing and management  
- Admin login panel for system controls  
- Responsive Bootstrap UI with form validation  
- Session-based user persistence  

## Tech Stack  
- PHP for backend logic and database interactions  
- MySQL for user/administrator data storage  
- JavaScript for client-side form validation  
- Bootstrap for frontend styling and layout  

## Installation  
1. Clone the repository to your local environment  
2. Create a MySQL database named 'mess_management'  
3. Create 'users' and 'admins' tables with appropriate fields (based on observed schema in queries)  
4. Configure `includes/connection.php` with your database credentials  
5. Start a local server (XAMPP, WAMP, or enable PHP on your host)  
6. Access the application via browser at `index.php`  

## Usage  
1. Visit `index.php` to register or login as a user  
2. Admin users can log in via the dedicated admin login interface  
3. Access personalized dashboards from `user_dashboard.php` or `admin pannel/admin_dashboard.php`  
4. Submit feedback through the feedback form on user dashboards  
5. Use profile editing forms to manage account information  

## Contributing  
Contributions welcome! Open issues or pull requests for improvements, security fixes, or new features.  

## License  
MIT License (default fallback license applied)