# 🏫 Django Online Course Assessment App

A **Django web application** that extends an online course platform with **exam and assessment features**.  
Built within Coursera **IBM Back-End Development Professional Certificate** as part of the **Django Application Development with SQL and Databases** course.  

This project demonstrates practical **full-stack Django development** skills, including database modeling, template customization, and building views for dynamic content.

---

## 🚀 Features

- **Custom Models**: Question, Choice, and Submission models for course exams  
- **Admin Integration**: Manage courses, questions, and exam submissions from the Django Admin site  
- **Dynamic Templates**: Updated course details page with questions and choices  
- **Exam Result Workflow**:
  - Submission form  
  - Automatic evaluation of answers  
  - Result display page with scores and feedback  

---

## 📋 Project Scenario from the course

You are a **newly onboarded full-stack developer** tasked with adding a new assessment feature to an existing online course app.  
Your responsibilities included:

1. Designing and implementing `Question`, `Choice`, and `Submission` models  
2. Creating a new course object with exam-related models in the admin site  
3. Updating the **course details template** to display questions and choices  
4. Building a **new exam result template** to show submission results  
5. Implementing Django views to handle submission and result evaluation  

---

## 🛠️ Tech Stack

- **Language**: Python (3.x)  
- **Framework**: Django (5.x)  
- **Database**: SQLite (default, can be swapped for PostgreSQL/MySQL)  
- **Frontend**: Django Templates + Bootstrap  
- **Version Control**: Git & GitHub  
- **Deployment Ready**: Configurable for cloud platforms (Heroku, IBM Cloud, etc.)  

---

## 📂 Repository Structure
django-online-course-assessment/

├── .git/                          # Git version control metadata

├── .gitignore                     # Ignored files and folders (env, caches, etc.)

├── final-cloud-app-with-database/ # Starter Django project from Coursera

│ ├── myproject/                   # Django project configuration (settings, urls, wsgi, etc.)

│ ├── onlinecourse/                # Main application logic (models, views, urls)

│ ├── static/                      # Static files (CSS, JS, images)

│ ├── LICENSE                      # License file

│ ├── manage.py                    # Django project entry point

│ ├── manifest.yml                 # Cloud deployment configuration

│ ├── Procfile                     # Deployment process definition (Heroku/Cloud)

│ ├── README.md                    # Starter documentation

│ ├── requirements.txt             # Python dependencies

│ └── runtime.txt                  # Runtime environment configuration (Python version)


## ⚡ Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Anton-Ch/django-online-course-assessment.git
cd django-online-course-assessment
```

### 2. Set up a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run migrations
```bash
python manage.py migrate
```
### 5. Start development server
```bash
python manage.py runserver
```
Visit 👉 http://localhost:8000

## 🧪 Example Workflow

Log into the Django Admin
Create a course and add questions & choices
Open course detail page → answer questions
Submit exam → view results and feedback instantly

## ✅ Learning Outcomes

Through this project, I practiced and demonstrated:
- Designing relational database schemas with Django ORM
- Writing function-based views and URL mappings
- Securing sensitive data with .env and .gitignore
- Integrating Bootstrap for responsive UI
- Applying MVC (Model-View-Controller) design patterns
- Using Git & GitHub for professional version control

🎓 About the Course

This project was developed as the final assignment in **Django Application Development with SQL and Databases** course, part of:
**IBM Back-End Development Professional Certificate**
