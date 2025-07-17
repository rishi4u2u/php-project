# Local Development Setup: PHP, MySQL, and Git Integration

As part of my internship tasks, I’ve set up the local development environment for PHP and MySQL, and configured version control using Git and GitHub.

## ✅ Environment Setup

**Tools Used:**
- PHP (local server via XAMPP)
- MySQL (via phpMyAdmin)
- Git for version control
- GitHub for remote repository

### 1. Local Server Configuration
- Installed and configured **XAMPP**.
- Project files placed in `htdocs/` directory.
- Apache and MySQL services started via XAMPP Control Panel.

### 2. Database Setup
- Created a MySQL database using **phpMyAdmin**.
- Updated database connection credentials in the PHP config file.

### 3. Running the Project
- Accessed via: `http://localhost/your-project-folder/`

## 🔄 Version Control

### 1. Initialized Git Repository
```bash
git init
git add .
git commit -m "Initial commit"

### 2. Connected to GitHub
git remote add origin https://github.com/your-username/your-repo.git
git branch -M main
git push -u origin main
