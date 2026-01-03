**🗂️ Task Management System**

A desktop-optimized Task Management System built with Django (backend) and React (frontend).
The application enables role-based task and project management for SuperManager, Manager, and Employee, allowing seamless task allocation and progress tracking.

----------------

**🚀 Live Demo**: https://task-flow-deployment.onrender.com/

**💻 GitHub Repository**: https://github.com/Lekashri-K/Task_flow_deployment

---------------------------

📸** Screenshots **

<table>
<tr>
<td>
<img src="https://github.com/user-attachments/assets/ec8ca8a8-cc8a-42ba-98da-b4e4654dce0b" alt="Home Page" width="550">
</td>
<td>
<img src="https://github.com/user-attachments/assets/57f2d76a-7910-4bae-aca9-f554943d53eb" alt="SuperManager Dashboard" width="550">
</td>
</tr>
<tr>
<td align="center">Home Page</td>
<td align="center">SuperManager Dashboard</td>
</tr>

<tr>
<td>
<img src="https://github.com/user-attachments/assets/f1ab4bcc-d247-4fe5-bec4-09b2e2273217" alt="Manager Task Allocation" width="550">
</td>
<td>
<img src="https://github.com/user-attachments/assets/6e9b52a9-39f4-4172-8b16-82d3b8af3ce2" alt="Employee Task Status Update" width="550">
</td>
</tr>
<tr>
<td align="center">Manager Task Allocation</td>
<td align="center">Employee Task Status Update</td>
</tr>
</table>

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

























