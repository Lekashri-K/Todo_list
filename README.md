🗂️ Task Management System

A desktop-optimized Task Management System built with Django (backend) and React (frontend).
The application allows role-based task and project management for SuperManager, Manager, and Employee, enabling seamless task allocation and tracking across an organization.

🚀 Live Demo
Click Here

💻 GitHub Repository
Click Here

📸 Screenshots

(Replace URLs with your actual images)

🌙 SuperManager Dashboard
<img src="https://via.placeholder.com/700x400" alt="SuperManager Dashboard" width="700">

📝 Manager Task Allocation
<img src="https://via.placeholder.com/700x400" alt="Manager Dashboard" width="700">

✅ Employee Task Status Update
<img src="https://via.placeholder.com/700x400" alt="Employee Dashboard" width="700">

🛠️ Technologies Used

Django (Backend & REST API)

Django REST Framework

React.js (Frontend)

JavaScript

SQLite (Database)

JWT Authentication

HTML5 & CSS3

✨ Features

✅ Role-based access control: SuperManager, Manager, Employee
✅ SuperManager Capabilities:

Create users

Create and assign projects to Managers

Create tasks and assign to Users
✅ Manager Capabilities:

Assign tasks to Employees

Track task progress within projects
✅ Employee Capabilities:

View assigned tasks

Update task status (e.g., Pending, In Progress, Completed)
✅ RESTful APIs for backend-frontend communication
✅ Real-time updates via React
✅ Desktop-optimized UI for task tracking and management

⚙️ How It Works

Backend: Django REST Framework handles authentication, task/project CRUD, and role-based access.

Frontend: React fetches APIs and dynamically renders dashboards for each role.

Roles Workflow:

SuperManager creates users and projects, assigns tasks to managers and users.

Manager receives assigned projects and allocates tasks to employees.

Employee updates the task status and tracks progress.

Database: SQLite stores all users, projects, tasks, and roles efficiently.

📂 Project Structure

Task_flow_deployment/
├─ backend/           # Django backend
│  ├─ manage.py
│  ├─ app/
│  └─ ...
├─ frontend/          # React frontend
│  ├─ src/
│  ├─ public/
│  └─ package.json
├─ README.md
└─ requirements.txt


🧪 Run Locally

Clone the repository

git clone https://github.com/Lekashri-K/Task_flow_deployment.git


Setup Backend

cd backend
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


Setup Frontend

cd frontend
npm install
npm start


Open your browser at http://localhost:3000 and start managing tasks 🚀

👩‍💻 Author

Leka Shri
GitHub
