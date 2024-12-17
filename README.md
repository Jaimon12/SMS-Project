School Management System (SMS)

This project is a School Management System (SMS) built using Django. It incorporates role-based access control (RBAC) to manage users and provide functionality tailored to different roles: Admin, Office Staff, and Librarian. The system allows CRUD operations for managing student details, library history, and fees history.


---

Features

Roles and Permissions

Admin

Full access to the system.

Manage (create, edit, delete) Office Staff and Librarian accounts.

Perform CRUD operations on students, library, and fees records.


Office Staff

View all student details.

Manage fees history.

View library records.


Librarian

View-only access to student and library history.



---

Authentication

Implemented using Django's built-in authentication framework.

Role-based access control using Django permissions and groups.



---

Dashboards

Admin Dashboard

Manage staff accounts.

Perform CRUD operations for student, library, and fees data.


Office Staff Dashboard

View student details.

Manage fees history.

View library history.


Librarian Dashboard

View student and library history.




---

Student Management

Create, update, view, and delete student details.


Library History

Manage borrowing records (add, edit, delete).


Fees History

Manage fee records (add, edit, delete).



---

Additional Features

Confirmation prompts for critical actions.

User session management with Django.



---

Installation Instructions

Prerequisites

Python 3.8 or higher

Django 5.1.1

Required dependencies listed in requirements.txt.



---

Setup

Clone the repository:

git clone https://github.com/Jaimon12/SMS-Project.git
cd SMS-Project

Install dependencies:

pip install -r requirements.txt

Set up the database:

python manage.py makemigrations
python manage.py migrate

Create a superuser:

python manage.py createsuperuser

Start the development server:

python manage.py runserver

Access the application at http://127.0.0.1:8000.


---

Environment Variables

Create a .env file in the project root with the following configuration:

SECRET_KEY=your_secret_key
DEBUG=True
ALLOWED_HOSTS=127.0.0.1


---

Libraries Used

Django 5.1.1

Django REST Framework

Django Filter

Django Allauth

Phonenumbers

PyJWT

SQLParse

PyCountry

JWCrypto


Full dependency list is available in requirements.txt.


---

Contribution

Feel free to fork the repository and submit pull requests to contribute!


---

Evaluation

This project adheres to Django best practices, including:

Proper folder structure.

MVC (Model-View-Controller) architecture.

Coding standards for scalability and maintainability.


