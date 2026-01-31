# schoolfile
# 🎓 School Management System

A comprehensive web-based school management system built with Flask, featuring student enrollment, teacher management, attendance tracking, grading, fee management, and more.

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- pip (Python package installer)

### Installation & Setup

1. **Navigate to the project directory:**
   ```bash
   cd school_management_system
   ```

2. **Run the automated setup:**
   ```bash
   python start.py
   ```

   This will:
   - Install all required dependencies
   - Initialize the database
   - Start the web server

3. **Access the application:**
   - Open your browser to: http://localhost:5000
   - Register your first admin account
   - Start managing your school!

## 📋 Features

### Core Management
- **Student Enrollment** - Register students with automatic fee generation
- **Teacher Management** - Add and manage teaching staff
- **Class Organization** - Create classes and assign teachers
- **Attendance Tracking** - Daily attendance with auto-load features
- **Grade Management** - Subject-wise grading and performance tracking
- **Fee Management** - Complete fee structure, payment tracking, challan printing
- **Library System** - Book catalog and loan management
- **Reports & Analytics** - Comprehensive reporting dashboard

### User System
- **Role-based Access** - Admin, Teacher, Student, Parent roles
- **Secure Authentication** - Login/logout with password protection
- **Custom Dashboards** - Different interfaces for each user type

## 🗂️ Project Structure

```
school_management_system/
├── app/
│   ├── __init__.py      # Flask app factory
│   ├── models.py        # Database models
│   ├── routes.py        # Application routes
│   └── forms.py         # WTForms definitions
├── templates/           # HTML templates
├── static/              # CSS, JS, images
├── school_management.db # SQLite database (created automatically)
├── run.py              # Application entry point
├── start.py            # Automated setup script
├── init_db.py          # Database initialization
└── requirements.txt    # Python dependencies
```

## 🔧 Manual Setup (Alternative)

If you prefer manual setup:

```bash
# Install dependencies
pip install -r requirements.txt

# Initialize database
python init_db.py

# Run the application
python run.py
```

## 💡 Usage Guide

### First Time Setup
1. **Register Admin Account** - The first user registered becomes an admin
2. **Set Fee Structures** - Define admission and monthly fees by grade
3. **Add Teachers** - Register teaching staff with subjects
4. **Create Classes** - Organize classes and assign teachers

### Daily Operations
1. **Enroll Students** - Add students (fees auto-generate based on grade)
2. **Mark Attendance** - Track daily attendance for classes
3. **Enter Grades** - Record student performance
4. **Manage Fees** - Track payments and generate challans
5. **Access Reports** - View comprehensive analytics

## 🔒 Security Features

- Password hashing with Werkzeug
- CSRF protection on all forms
- Role-based access control
- Session management
- SQL injection prevention

## 💾 Data Persistence

- All data is stored in SQLite database (`school_management.db`)
- Data persists between sessions
- Backup the database file for data safety

## 🛠️ Technologies Used

- **Backend:** Flask, SQLAlchemy, Flask-Login, Flask-WTF
- **Database:** SQLite
- **Frontend:** Bootstrap 5, HTML5, CSS3
- **Security:** Werkzeug, CSRF Protection

## 📞 Support

The system includes comprehensive error handling and user-friendly interfaces. All features are fully functional and ready for production use.

## 📝 License

This project is open-source and available for educational and commercial use.
