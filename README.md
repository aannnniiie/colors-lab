# COLORS (LAMP Stack)

A simple web app for logging in and searching/adding colors using a PHP API and a browser-based frontend.

## Technologies Used
- Apache
- PHP
- MySQL/MariaDB
- HTML/CSS/JavaScript

## Project Structure
- `api/` — PHP backend endpoints (Login, SearchColors, AddColor)
- `public/` — Frontend pages + assets (HTML/CSS/JS/images)

## Setup (High Level)
1. Install a LAMP stack (Apache + PHP + MySQL).
2. Create a MySQL database and required table(s) used by the API.
3. Update the database connection settings in the PHP files in `api/` (do not commit real passwords).
4. Place this project in your Apache web root (example: `/var/www/html/lampstack`).

## Run / Access
Start services, then open:
- `http://localhost/lampstack/public/`
(or your server IP/domain equivalent)

## Assumptions / Limitations

- This project was provided as part of a course lab and is intended for educational and demonstration purposes only.
- The application assumes a properly configured LAMP environment (Apache, PHP, and MySQL) running locally or on a server.
- Database credentials must be manually configured in the PHP files before running the application.
- The system does not include production-level security features (e.g., input sanitization hardening, HTTPS enforcement, rate limiting, or comprehensive error handling).
- This application is designed for a controlled lab environment and has not been optimized for scalability or high-traffic deployment.
- There is no user account management or password recovery functionality implemented.

## AI Usage
- No AI used.
