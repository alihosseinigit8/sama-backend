# Professor-TA Connector (Django REST Framework Backend)

🚀 **A backend system to help professors find and manage Teaching Assistants (TAs) for their courses.**

full project can be found here https://github.com/SE402-G4/Software-Engineering-Project/tree/main

## Features

✔ **Professor-TA Matching**: Efficiently connect professors with qualified TAs based on course requirements.  
✔ **Automated Workflow**: Streamline TA hiring, assignments, and communication.  
✔ **Role-Based Access**: Secure endpoints for professors, TAs, and admins.  
✔ **Scalable API**: Built with Django REST Framework for robustness and flexibility.  

## Use Cases

- Universities needing a structured TA allocation system  
- Professors searching for TAs with specific skills (e.g., grading, lab assistance)  
- Departments managing TA workloads and performance  

## Tech Stack

**Backend**: Django REST Framework  
**Database**: PostgreSQL (default) / SQLite (dev)  
**Authentication**: JWT (via SimpleJWT)  
**Deployment**: Docker-ready  

## Installation

```bash
git clone https://github.com/yourusername/sama-backend.git
cd sama-backend
python -m venv venv
source venv/bin/activate  # Linux/Mac | venv\Scripts\activate for Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## API Documentation
http://127.0.0.1:8000/swagger/
![image](https://github.com/user-attachments/assets/69a3f4b1-cf11-4ec4-9c77-0f030d193ade)
![image](https://github.com/user-attachments/assets/bfe2e12c-4f23-43c4-8924-af8447f12f3f)
![image](https://github.com/user-attachments/assets/c536c2d1-187a-4f2e-976d-c9b95c5da9d9)


