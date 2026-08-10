# Flask Student CRUD

A simple, lightweight web application built with Python and Flask to manage student records. It demonstrates standard Create, Read, Update, and Delete (CRUD) operations using SQLAlchemy and a local SQLite database.

## Features

- **Create:** Add new students with their name, email, phone, and course.
- **Read:** View a formatted table of all enrolled students.
- **Update:** Edit existing student information.
- **Delete:** Remove a student from the database safely.
- **Zero-Config Database:** Uses a local SQLite file (`app.db`), requiring no external database servers or passwords.
- **Responsive UI:** Styled with Bootstrap 5.

## Tech Stack

- **Backend:** Python, Flask
- **Database:** SQLite, Flask-SQLAlchemy (ORM)
- **Frontend:** HTML, Bootstrap 5

## How to Run Locally

1. **Clone the repository**
   ```bash
   git clone [https://github.com/ShantanuSomwanshi/crud.git](https://github.com/ShantanuSomwanshi/crud.git)
   cd crud
   Create and activate a virtual environment
   ```

Bash
python -m venv venv

# On Windows:

venv\Scripts\activate

# On Mac/Linux:

source venv/bin/activate
Install dependencies

Bash
pip install -r requirements.txt
Run the application

Bash
python app.py
Note: The database file (app.db) will be generated automatically the very first time you start the server.

View the app
Open your browser and navigate to http://localhost:5000
