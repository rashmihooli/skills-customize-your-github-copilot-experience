# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and test RESTful APIs using the FastAPI framework in Python. You will create a simple API for managing a collection of resources, practicing endpoint creation, request handling, and response formatting.

## 📝 Tasks

### 🛠️	Task 1: Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and verify that the server runs locally.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main Python file (e.g., `main.py`) with a basic FastAPI app
- Add a root endpoint (`/`) that returns a welcome message
- Run the server locally and test the root endpoint


### 🛠️	Task 2: Implement CRUD Endpoints

#### Description
Create RESTful endpoints to manage a list of items (e.g., books, tasks, or students). Implement Create, Read, Update, and Delete (CRUD) operations.

#### Requirements
Completed program should:

- Define a Pydantic model for the resource (e.g., `Item`)
- Implement endpoints for:
  - Listing all items (`GET /items`)
  - Adding a new item (`POST /items`)
  - Retrieving a single item by ID (`GET /items/{item_id}`)
  - Updating an item by ID (`PUT /items/{item_id}`)
  - Deleting an item by ID (`DELETE /items/{item_id}`)
- Return appropriate status codes and JSON responses


### 🛠️	Task 3: (Optional) Add Validation and Error Handling

#### Description
Enhance your API with input validation and custom error responses.

#### Requirements
Completed program could:

- Validate input data using Pydantic
- Return helpful error messages for invalid requests
- Handle cases where an item is not found
