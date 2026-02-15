# 📝 Advanced To-Do List Application (Python CLI)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)


A command-line based task management application built using Python.  
This application allows users to efficiently create, manage, and track tasks with persistent storage using JSON.

---
📌 Project Overview:-

✔Project Type  : Command Line Interface (CLI)
✔Language      : Python 3
✔Architecture  : Object-Oriented Programming (OOP)
✔Storage       : JSON-based local persistence
✔Version Ctrl  : Git & GitHub
✔Editor        : VS Code


This project demonstrates:

✔Object-Oriented Programming (OOP)
✔File handling & JSON storage
✔Exception handling
✔Modular project structure
✔Clean code practices
✔Version control workflow

🚀 Features:

[+] Add Task
    - Title
    - Priority (Low / Medium / High)
    - Due Date

[•] View Tasks
    - Displays all tasks in structured format

[✔] Complete Task
    - Marks selected task as completed

[-] Delete Task
    - Removes task from list

[💾] Persistent Storage
    - Automatically saves tasks to JSON file

[⚠] Error Handling
    - Handles missing or corrupted files gracefully

🛠 Technologies Used:

Python 3
JSON Module
OS Module
Datetime Module
Git
GitHub
VS Code

📂 Project Structure:

Advanced-To-Do-List-Application/
│
├── main.py
├── task_manager.py
├── requirements.txt
└── README.md

Note:
- tasks.json is auto-generated at runtime.
- It is excluded from version control using .gitignore.
- This keeps the repository clean and professional.

⚙️ Application Workflow:
1. Program starts
2. TaskManager class initializes
3. Existing tasks loaded (if file exists)
4. User selects operation from menu
5. Tasks updated accordingly
6. Changes saved automatically to JSON


Each Task Object Contains:
{
    "title": "Task Name",
    "priority": "High/Medium/Low",
    "due_date": "YYYY-MM-DD",
    "completed": true/false,
    "created_at": "timestamp"
}

▶️ Installation & Execution:

✔Clone Repository:- git clone https://github.com/princiloura14/to-do-list-codsoft.git
✔Navigate to Directory:- cd to-do-list-codsoft
✔Run Application:- python main.py

📚 Learning Outcomes:

✔ Applied OOP principles in real project
✔ Implemented persistent storage using JSON
✔ Handled file-based exceptions
✔ Structured CLI application professionally
✔ Practiced Git workflow (add, commit, push)
✔ Wrote production-style README documentation

👩‍💻 Author:-

Name    : Princi Loura
Role    : Aspiring DevOps and Cloud Engineer
GitHub  : https://github.com/princiloura14



