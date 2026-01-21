# Job Portal Website
### A full-stack Job Portal Web Application built using **Python Django** that connects job seekers with employers. The platform provides job searching, filtering, application tracking, employer job posting, and real-time chatbot assistance. 
--- 
## Features 
### Job Seekers 
- User registration, login, and logout
- Search jobs by category, location and jobtype
- Apply for jobs and track applied jobs
- Upload resumes based on interests
- Personalized applied jobs dashboard
### Employers 
- Post and manage job openings
- View and manage applications
- Role-based access and redirection
### Chatbot 
- Real-time assistance for job-related queries
- Helps users navigate the platform easily
### Email Verification 
- Ensures secure and valid user accounts
---
## Pages Implemented
- Home Page (dynamic content based on user role)
- Sign Up Page (custom Django User Creation Form)
- Login / Sign-In Page
- Job Listings Page
- Categories Page
- Applied Jobs Page
- Contact Page (with form validation and confirmation)
- About Page
---
## Tech Stack
**Backend** 
- Python
- Django
   
**Frontend**
- HTML
- CSS
- Bootstrap
  
**Database** 
- MySQL
  
**Other Tools** 
- Django Authentication System
- Django ORM
---
## Project Structure

```text
JobFolder/
│
├── jobportalvenv/              # Virtual environment
│
├── Jobproject/                # Main Django project
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── AdminApp/                  # Admin & Employer-related functionalities
│   ├── migrations/
│   ├── templates/
│   │   ├── AddCategory.html
│   │   ├── AddCompany.html
│   │   ├── AddJob.html
│   │   ├── AdminLoginPage.html
│   │   ├── DisplayCategory.html
│   │   ├── DisplayCompany.html
│   │   ├── DisplayJob.html
│   │   ├── EditCategory.html
│   │   ├── EditCompany.html
│   │   ├── EditJob.html
│   │   └── index.html
│   ├── static/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── WebApp/                    # Job Seeker & Public-facing functionalities
│   ├── migrations/
│   ├── templates/
│   │   ├── Home.html
│   │   ├── Jobs.html
│   │   ├── Filtered_items.html
│   │   ├── Single_item.html
│   │   ├── Applied.html
│   │   ├── Contact.html
│   │   ├── About.html
│   │   ├── Sign_Up.html
│   │   └── Sign_In.html
│   ├── static/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── media/                     # Uploaded resumes & files
├── db.sqlite3                 # Database
├── manage.py
├── requirements.txt
└── README.md
```
---
## Installation & Setup
### 1.Create and activate virtual environment
- python -m venv jobportalvenv
- jobportalvenv\Scripts\activate   # Windows
### 2.Install dependencies
- pip install -r requirements.txt
### 3.Apply migrations
- python manage.py makemigrations
- python manage.py migrate
### 4.Run the development server
- python manage.py runserver
### 5.Access the application
- http://127.0.0.1:8000/
