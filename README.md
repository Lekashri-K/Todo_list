🗂️ Task Management System

A desktop-optimized Task Management System built with Django (backend) and React (frontend).
The application enables role-based task and project management for SuperManager, Manager, and Employee, allowing seamless task allocation and progress tracking.

----------------

🚀 Live Demo
https://task-flow-deployment.onrender.com/

💻 GitHub Repository
https://github.com/Lekashri-K/Task_flow_deployment

---------------------------

📸 Screenshots

<img width="1755" height="1831" alt="image" src="https://github.com/user-attachments/assets/ec8ca8a8-cc8a-42ba-98da-b4e4654dce0b" />

🌙 SuperManager Dashboard
🧑‍💼 SuperManager View

<table>
<tr>
<td><img src="https://github.com/user-attachments/assets/57f2d76a-7910-4bae-aca9-f554943d53eb" width="380"></td>
<td><img src="https://github.com/user-attachments/assets/40ccb368-1961-40f1-9aa0-4153ee24d155" width="380"></td>
</tr>
<tr>
<td align="center">Dashboard Overview</td>
<td align="center">User Management</td>
</tr>

<tr>
<td><img src="https://github.com/user-attachments/assets/5b87caa6-de84-48a5-af57-52c41ca1f20c" width="380"></td>
<td><img src="https://github.com/user-attachments/assets/4aff42b1-0821-4c99-b651-a6257bfc7fcd" width="380"></td>
</tr>
<tr>
<td align="center">Project Creation</td>
<td align="center">Task Assignment</td>
</tr>

<tr>
<td colspan="2" align="center">
<img src="https://github.com/user-attachments/assets/fe3f995c-f79c-48d0-916c-6596b838b095" width="500">
</td>
</tr>
<tr>
<td colspan="2" align="center">Overall Management View</td>
</tr>
</table>



📝 Manager Task Allocation
<img src="https://via.placeholder.com/700x400" alt="Manager Dashboard" width="700">

✅ Employee Task Status Update
<img src="https://via.placeholder.com/700x400" alt="Employee Dashboard" width="700">

---------------------------------

🛠️ Technologies Used

- Django (Backend & REST API)

- Django REST Framework

- React.js (Frontend)

- JavaScript

- SQLite (Database)

- JWT Authentication

- HTML & CSS

-----------------------------

✨ Features

✅ Role-based access control: SuperManager, Manager, Employee

✅ SuperManager Capabilities:

    - Create users

    - Create and assign projects to Managers

    - Create tasks and assign to Users

✅ Manager Capabilities:

    - Assign tasks to Employees

    - Track task progress within projects

✅ Employee Capabilities:

    - View assigned tasks

    - Update task status (Pending, In Progress, Completed)

✅ RESTful APIs for backend-frontend communication

✅ Real-time updates via React

✅ Desktop-optimized UI for task tracking and management

----------------------

⚙️ How It Works

- Backend: Django REST Framework handles authentication, task/project CRUD, and role-based access.

- Frontend: React fetches APIs and dynamically renders dashboards for each role.

- Roles Workflow:

    - SuperManager: creates users, projects, and tasks, assigning them to Managers and Employees

    - Manager: allocates tasks to employees and monitors progress

    - Employee: updates task status and tracks progress

- Database: SQLite stores all users, projects, tasks, and roles efficiently

---------------------------

Project Structure

    Task_flow_deployment/
    ├─ backend/
    │  ├─ manage.py
    │  └─ app/
    ├─ frontend/
    │  ├─ src/
    │  └─ package.json
    ├─ README.md
    └─ .gitignore


------------------------------------

🧪 Run Locally

1. Clone the repository

    git clone https://github.com/Lekashri-K/Task_flow_deployment.git


2. Setup Backend

    cd backend
    python -m venv venv
    source venv/bin/activate   # or venv\Scripts\activate on Windows
    pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver


3. Setup Frontend

    cd frontend
    npm install
    npm start


4. Open your browser at http://localhost:3000 and start managing tasks 🚀

-----------------------------

👩‍💻 Author

Lekashri  
[GitHub](https://github.com/Lekashri-K)

















