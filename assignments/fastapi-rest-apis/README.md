# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API using FastAPI to practice routing, request/response models, and basic in-memory data management.

## 📝 Tasks

### 🛠️	Create Core API Endpoints

#### Description
Create a FastAPI application that manages a simple collection of books. You will implement endpoints to create, read, update, and delete books.

#### Requirements
Completed program should:

- Create a FastAPI app in `starter-code.py` and run it with Uvicorn.
- Define endpoints for `GET /books`, `GET /books/{book_id}`, `POST /books`, `PUT /books/{book_id}`, and `DELETE /books/{book_id}`.
- Return correct HTTP status codes (for example, `404` when a book is not found).


### 🛠️	Validate Data with Pydantic Models

#### Description
Add request and response validation using Pydantic models so the API only accepts well-structured book data.

#### Requirements
Completed program should:

- Create a `BookCreate` model for incoming data with fields: `title`, `author`, and `year`.
- Create a `Book` model for stored/returned data that includes an `id` field.
- Ensure invalid payloads are automatically rejected with validation errors.
