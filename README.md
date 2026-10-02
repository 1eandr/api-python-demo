# API Python Demo

**Python | FastAPI | REST API**

---

## About

Simple REST API built with Python and FastAPI. Demonstrates backend development skills including routing, request handling, and JSON responses.

---

## What It Does

- CRUD operations for tasks
- Input validation
- Automatic API documentation
- Error handling

---

## Tech Stack

`Python` `FastAPI` `Uvicorn` `Pydantic`

---

## How to Run

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

API docs: http://localhost:8000/docs

---

## Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /tasks | List all tasks |
| POST | /tasks | Create a new task |
| GET | /tasks/{id} | Get task by ID |
| PUT | /tasks/{id} | Update task |
| DELETE | /tasks/{id} | Delete task |

---

## Learning Goals

- Understand REST API design
- Learn async Python
- Practice input validation
- Build backend services

---

> "APIs are the backbone of modern software — learn them well."
