# Quick Virtual Card

Quick Virtual Card is a PHP and JavaScript-based web application designed to create and manage digital business cards. The platform includes user management, an administration system, and multilingual functionality to provide an accessible and user-friendly experience.

## Features

- **User Management:** User registration, login, account settings, and password recovery.
- **Virtual Card Management:** Create and manage digital business cards using different templates.
- **QR Code Generator:** Generate QR codes to make sharing digital business cards easier.
- **Admin Dashboard:** Manage users and administrator accounts through a dedicated administration panel.
- **Role Management:** Support for different user roles and administrative access.
- **Membership System:** Manage membership plans and related payment functionality.
- **Transaction Management:** View transaction details and invoices.
- **Multilingual Support:** Provide language options for a wider range of users.
- **Responsive Interface:** User-friendly interface designed for different screen sizes.

## Technology Stack

| Technology | Purpose |
|---|---|
| PHP | Backend development |
| JavaScript | Interactive functionality |
| HTML5 | Page structure |
| CSS3 | Styling and layout |
| Bootstrap | Responsive design |
| jQuery | Dynamic interactions and AJAX |
| MySQL | Database management |
| AltoRouter | URL routing |
| Idiorm | Database query management |

## Project Structure

```text
QuickVirtualCard/
│
├── admin/                  # Administration panel
├── includes/               # Configuration, database and helper files
├── php/                    # Main application logic
├── templates/              # Website templates and themes
├── vcard-templates/        # Virtual card designs
├── install/                # Installation files
├── index.php               # Main application entry point
└── .htaccess               # Server configuration
```

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/aaryagoriya/QuickVirtualCard.git
```

### 2. Navigate to the Project Directory

```bash
cd QuickVirtualCard
```

### 3. Set Up the Local Server

- Install XAMPP or another PHP-compatible web server.
- Start Apache and MySQL.
- Move the project folder into the server's document root.

For XAMPP:

```text
C:\xampp\htdocs\QuickVirtualCard
```

### 4. Create the Database

- Open phpMyAdmin.
- Create a new database for the application.
- Configure the database connection details in the application configuration.

### 5. Run the Application

Open the following URL in your browser:

```text
http://localhost/QuickVirtualCard/
```

If the application is not installed, it should redirect you to the installation page. Follow the on-screen instructions to complete the setup.

## Future Improvements

- Improve the overall user interface and user experience.
- Enhance security and authentication mechanisms.
- Improve mobile responsiveness.
- Add additional virtual card templates.
- Improve multilingual functionality.
- Introduce automated testing.

## Project Information

- **Project Name:** Quick Virtual Card
- **Development:** Web Application Development
- **Technologies:** PHP, JavaScript, HTML, CSS, MySQL
- **Focus:** Virtual Business Cards, Role Management and Multilingual Support

---

Developed as a web development project focused on building a digital business card platform with user management, administrative functionality, and multilingual accessibility.
