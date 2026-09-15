# Northwind — Project Management System

Northwind is a modern **Project Management System** designed to help teams organize projects, manage tasks, track progress, and collaborate more efficiently.

The project focuses on providing a structured workflow for managing projects from creation to completion, with a clean and intuitive user interface.

---

## ✨ Features

### 📁 Project Management

* Create and manage projects
* View project details and progress
* Organize projects in a centralized dashboard
* Track project status and deadlines

### ✅ Task Management

* Create, edit, and delete tasks
* Assign tasks to team members
* Set task priorities
* Track task status
* Manage task deadlines
* Organize tasks within projects

### 👥 Team Management

* Manage project members
* Assign responsibilities to team members
* Track team participation across projects

### 📊 Dashboard

* Overview of active projects
* Task statistics
* Project progress
* Upcoming deadlines
* Quick access to important project information

### 🔐 Authentication

* User registration
* User login/logout
* Secure authentication
* User-specific project and task access

### 📱 Responsive Interface

* Responsive design for different screen sizes
* Clean and modern UI
* Easy navigation
* User-focused experience

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Responsive Web Design

### Backend

* Python
* Django

### Database

* SQLite / PostgreSQL

### Development Tools

* Git
* GitHub
* VS Code

---

## 🏗️ Project Architecture

The project follows a structured full-stack architecture:

```text
Northwind/
│
├── backend/
│   ├── manage.py
│   ├── project/
│   ├── apps/
│   └── ...
│
├── frontend/
│   ├── templates/
│   ├── static/
│   ├── css/
│   └── js/
│
├── requirements.txt
├── .gitignore
└── README.md
```

> The exact structure may vary depending on the current project implementation.

---

## 🚀 Getting Started

Follow the steps below to run Northwind locally.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/northwind.git
```

Move into the project directory:

```bash
cd northwind
```

---

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment.

#### Windows

```bash
venv\Scripts\activate
```

#### macOS / Linux

```bash
source venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Configure environment variables

Create a `.env` file in the project root:

```env
SECRET_KEY=your-secret-key
DEBUG=True
DATABASE_URL=your-database-url
```

For local development, you can configure the database according to the project's settings.

> Never commit sensitive environment variables or secret keys to GitHub.

---

### 5. Run database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 6. Create an admin user

```bash
python manage.py createsuperuser
```

Follow the instructions in the terminal.

---

### 7. Start the development server

```bash
python manage.py runserver
```

The application will be available at:

```text
http://127.0.0.1:8000/
```

---

## 🔄 Application Workflow

A typical workflow inside Northwind looks like this:

```text
User
 │
 ▼
Authentication
 │
 ▼
Dashboard
 │
 ├── Projects
 │     └── Project Details
 │            └── Tasks
 │
 ├── Team Members
 │
 └── Task Management
        │
        ├── Pending
        ├── In Progress
        └── Completed
```

This structure allows users to manage their work through a clear project → task workflow.

---

## 📊 Project Management Flow

```text
Create Project
      │
      ▼
Add Team Members
      │
      ▼
Create Tasks
      │
      ▼
Assign Tasks
      │
      ▼
Track Progress
      │
      ▼
Complete Tasks
      │
      ▼
Complete Project
```

---

## 🎯 Goals

The main goals of Northwind are:

* Simplify project organization
* Improve task management
* Provide better visibility into project progress
* Make team responsibilities easier to manage
* Provide a centralized workspace for projects and tasks
* Create a practical full-stack application using Django

---

## 🧩 Key Concepts Demonstrated

This project demonstrates practical experience with:

* Full-stack web development
* Django application architecture
* CRUD operations
* Database modeling and relationships
* Authentication and authorization
* RESTful development concepts
* Frontend/backend integration
* Responsive UI development
* Form handling and validation
* Git and version control
* Deployment-ready project structure

---

## 🔒 Security

The project follows common web security practices, including:

* Environment variables for sensitive configuration
* Django authentication system
* CSRF protection
* Server-side validation
* Permission-based access to project data
* Secure handling of application secrets

For production deployment, additional security configuration should be enabled, including:

* `DEBUG=False`
* Secure cookies
* HTTPS
* Proper `ALLOWED_HOSTS`
* Production database configuration

---

## 🧪 Testing

Tests can be executed using Django's built-in testing framework:

```bash
python manage.py test
```

Additional tests can be added for:

* Authentication
* Project creation
* Task management
* User permissions
* Database relationships
* API endpoints

---

## 📌 Future Improvements

Potential future improvements include:

* Real-time notifications
* Task comments
* File attachments
* Activity logs
* Advanced project analytics
* Kanban board
* Calendar view
* Email notifications
* Role-based permissions
* REST API
* Mobile-friendly improvements
* Dark mode
* Advanced search and filtering

---

## 📷 Screenshots

Add screenshots of the main application here.

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Project Details

![Project Details](screenshots/project-details.png)

### Task Management

![Task Management](screenshots/tasks.png)

---

## 💡 Why Northwind?

Northwind was built as a practical full-stack project to demonstrate how a real-world project management platform can be designed and developed.

Instead of focusing only on individual features, the project brings together authentication, database design, project management, task workflows, UI development, and backend logic into a single application.

---

## 👨‍💻 Developer

**Amin Esmaeilzadeh**

Full-Stack Developer focused on:

* Python
* Django
* JavaScript
* Machine Learning
* UI/UX
* Modern Web Development

---

## 📄 License

This project is available for educational and portfolio purposes.

If you plan to reuse or modify the project, please check the repository's license and attribution requirements.

---

⭐ If you find this project useful, consider giving the repository a star.
