# UserAuthProject

A Django based web application for user authentication and role-based dashboard system.



## Features

- Signup and Login system
- Two types of users: 
  - Patient
  - Doctor
- Profile Picture upload
- User information collected:
  - First Name
  - Last Name
  - Username
  - Email
  - Password
  - Address (Line 1, City, State, Pincode)
- Role-based dashboards after login
- Password and Confirm Password validation
- Django built-in authentication system used


## Tech Stack

- Django (Backend)
- SQLite (Database)
- HTML, CSS, Bootstrap (Frontend)

## Setup Instructions

1. Clone the repository:git clone https://github.com/garimasingh7842/UserAuthProject.git

2. Create and activate virtual environment:python -m venv myenv
                                            myenv\Scripts\activate (For Windows)
                                     
3. Install dependencies:

4. Apply migrations:python manage.py makemigrations
                    python manage.py migrate
   
5. Run server:python manage.py runserver
  
6. Visit:  http://127.0.0.1:8000/`













