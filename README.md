# PHP & MySQL Local Development Setup

## Prerequisites

- PHP
- MySQL
- Git
- A web server (e.g., XAMPP, MAMP, or Laragon)

## Setup Instructions

1. **Start Local Server:**
   - Start Apache and MySQL using XAMPP/MAMP/Laragon.
   - Place project files in the server's root directory (e.g., `htdocs/`).

2. **Configure Database:**
   - Create a database using phpMyAdmin or MySQL CLI.
   - Update database connection settings in your PHP code.

3. **Run Project:**
   - Open `http://localhost/your-project-folder` in your browser.

## Version Control with Git & GitHub

1. **Initialize Git:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/your-username/your-repo.git
   git branch -M main
   git push -u origin main   