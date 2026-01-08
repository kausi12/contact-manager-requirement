📇 Contacts Manager – CRUD Web Application

A lightweight CRUD (Create, Read, Delete) web application built using Flask and SQLite that allows users to manage contact information efficiently.
This project is developed as part of a Web Developer Assignment to demonstrate backend logic, validation, persistence, and basic UI/UX skills.

🔗 Project Overview

The Contacts Manager application enables users to:

Add new contacts

View a list of saved contacts

Delete existing contacts

Ensure data validation and uniqueness

The application follows a clean structure and uses a relational database for persistent storage.

✨ Features
Core Features

✅ Create new contact (Name, Email, Phone)

✅ View all contacts in a tabular format

✅ Delete contact

✅ Email format validation

✅ Prevent duplicate email entries

✅ Persistent storage using SQLite

✅ Clean and user-friendly interface

Error Handling

Displays clear validation messages

Prevents empty fields

Handles duplicate email submission gracefully

🧰 Tech Stack
Layer	Technology
Backend	Python (Flask)
Database	SQLite
ORM	SQLAlchemy
Frontend	HTML, CSS
Tools	Virtualenv
📁 Project Structure
contacts_manager/
│
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
├── contacts.db            # SQLite database (auto-generated)
│
└── templates/
    └── index.html         # UI template

⚙️ Setup & Run Instructions
Step 1: Extract / Clone the Project

If using ZIP:

unzip Contacts_Manager_Submission.zip
cd contacts_manager


If using Git:

git clone <repository_url>
cd contacts_manager

Step 2: Create Virtual Environment (Recommended)
python -m venv venv


Activate virtual environment:

Windows

venv\Scripts\activate


macOS / Linux

source venv/bin/activate

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Run the Application
python app.py


The SQLite database (contacts.db) will be created automatically on first run.

Step 5: Access the Application

Open your browser and visit:

http://127.0.0.1:5000/

🧪 Validation Rules

All fields are mandatory

Email must follow valid email format

Email must be unique

Phone number must not be empty

📌 API Behavior (Internal)

Form submission handled via Flask routes

SQLAlchemy ORM used for database operations

Server-side validation implemented before database insertion

🚀 Future Enhancements

Edit / Update contact

Search and filter contacts

Pagination

RESTful API endpoints

Authentication (Login/JWT)

Docker support

Unit & integration testing

CI/CD pipeline

👩‍💻 Author

Sukanya Jha
B.Tech – Computer Science & Engineering
📍 Kanpur, India

📄 License

This project is created for educational and evaluation purposes.
