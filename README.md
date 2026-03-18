# 🚀 Task Manager API

A simple RESTful Task Manager API built with FastAPI.

## 📌 Features
- Create tasks
- Retrieve all tasks
- Update tasks
- Delete tasks

## 🛠️ Tech Stack
- Python
- FastAPI
- Uvicorn

## 📡 API Endpoints

| Method | Endpoint        | Description        |
|--------|----------------|--------------------|
| GET    | /tasks         | Get all tasks      |
| POST   | /tasks         | Create a new task  |
| PUT    | /tasks/{id}    | Update a task      |
| DELETE | /tasks/{id}    | Delete a task      |

## ▶️ How to Run

```bash
pip install fastapi uvicorn
uvicorn main:app --reload
