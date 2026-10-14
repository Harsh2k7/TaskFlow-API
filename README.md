# 🚀 Multi-Agent Productivity Assistant

A lightweight task management API built with **Python, FastAPI, and SQLite**, designed to organize tasks through RESTful endpoints and basic agent-based task handling.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.14+-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Database-SQLite-003B57?logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/API-REST-orange" />
  <img src="https://img.shields.io/badge/Status-Development-yellow" />
</p>

## 📌 Overview

The Multi-Agent Productivity Assistant is a Python-based backend project that provides a simple way to create and retrieve tasks through API endpoints. It includes basic agent-based request handling and initial scheduling-response functionality.

The project is designed to demonstrate backend development, API design, database integration, and modular task processing.

## ✨ Features

- ✅ Create tasks through a REST API.
- 📋 Retrieve saved tasks.
- 🧠 Basic agent-based task handling.
- 📅 Initial scheduling-response functionality.
- 💾 SQLite database integration.
- 📚 Interactive API documentation with Swagger UI.
- ⚡ Lightweight backend built with FastAPI.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| FastAPI | REST API development |
| SQLite | Task data storage |
| Uvicorn | ASGI server |
| Swagger UI | API testing and documentation |

## 📂 Project Structure

```text
TaskFlow-API/
├── main.py
├── requirements.txt
├── README.md
└── tasks.db
```

*Note: The exact files may vary depending on your local project setup. Include `tasks.db` only if you intend to share the database file.*

## ⚙️ Getting Started

### Prerequisites

- Python 3.10 or a compatible version supported by your dependencies.
- pip package manager.
- Git.

### 1. Clone the Repository

```bash
git clone https://github.com/Harsh2k7/TaskFlow-API.git
cd TaskFlow-API
```

### 2. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Start the API Server

```bash
python -m uvicorn main:app --reload
```

### 4. Open API Documentation

Once the server starts, visit:

- **Swagger UI:** http://127.0.0.1:8000/docs
- **OpenAPI Schema:** http://127.0.0.1:8000/openapi.json

## 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/task` | Create a task |
| GET | `/tasks` | Retrieve tasks |

### Example Workflow

1. Open Swagger UI at `/docs`.
2. Expand `POST /task` and click **Try it out**.
3. Enter the request data required by the API schema and click **Execute**.
4. Call `GET /tasks` to view the stored tasks.

*The required request fields depend on the implementation in `main.py`.*

## 🧠 Project Goals

- Understand REST API development using FastAPI.
- Practice database integration with SQLite.
- Explore modular, agent-based request handling.
- Build a foundation for future productivity automation features.

## 🔮 Future Improvements

- Add task updates and deletion.
- Support deadlines, priorities, and task status.
- Integrate calendar services for actual event creation.
- Implement automated reminders and notifications.
- Add an interactive web dashboard.
- Expand agent capabilities with AI integration.

*These are planned enhancements and are not necessarily implemented yet.*

## 👨‍💻 Author

**Harsh Mishra**

- GitHub: [@Harsh2k7](https://github.com/Harsh2k7)
- Project: [TaskFlow-API](https://github.com/Harsh2k7/TaskFlow-API)

---

<p align="center">
  Built with Python and FastAPI.
</p>
