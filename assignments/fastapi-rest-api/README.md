# 📘 Assignment: FastAPI REST APIs

## 🎯 Objective

Build a small REST API using FastAPI to practice routing, request validation, and JSON responses.

## 📝 Tasks

### 🛠️ Project Setup and Data Model

#### Description
Create a new FastAPI app, define a simple data model, and prepare an in-memory list to store items.

#### Requirements
Completed program should:

- Create a FastAPI app instance in a Python file.
- Define a `Task` model with `id`, `title`, and `completed` fields.
- Store tasks in a list or dictionary during runtime.

### 🛠️ CRUD Endpoints

#### Description
Implement endpoints to create, read, update, and delete tasks, returning clear JSON responses.

#### Requirements
Completed program should:

- Create a task with `POST /tasks` and return the new task.
- List all tasks with `GET /tasks`.
- Update a task with `PUT /tasks/{id}`.
- Delete a task with `DELETE /tasks/{id}`.
- Return a helpful error message if a task id does not exist.
