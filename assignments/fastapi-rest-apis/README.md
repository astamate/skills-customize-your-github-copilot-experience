# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API using the FastAPI framework in Python. Learn about API design, routing, request/response handling, data validation, and CRUD operations to create a functional web service.

## 📝 Tasks

### 🛠️	Set Up FastAPI Project

#### Description
Initialize a new FastAPI project with the necessary dependencies and create the basic application structure.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn dependencies
- Create a FastAPI application instance
- Set up a basic root endpoint that returns a welcome message
- Run the development server successfully


### 🛠️	Create Data Models

#### Description
Define Pydantic models for data validation and structure the data that your API will handle.

#### Requirements
Completed program should:

- Create at least one Pydantic BaseModel for API data
- Include appropriate field types and validation
- Use the model in API endpoints for request/response handling


### 🛠️	Implement CRUD Endpoints

#### Description
Create REST API endpoints for Create, Read, Update, and Delete operations on your data.

#### Requirements
Completed program should:

- Implement GET endpoint to retrieve data (single item or list)
- Implement POST endpoint to create new data items
- Implement PUT/PATCH endpoint to update existing data
- Implement DELETE endpoint to remove data items
- Use appropriate HTTP status codes for responses


### 🛠️	Add Request Validation and Error Handling

#### Description
Enhance the API with proper input validation, error handling, and meaningful error responses.

#### Requirements
Completed program should:

- Validate incoming request data using Pydantic models
- Handle common errors (404 Not Found, 400 Bad Request, etc.)
- Return structured error responses with appropriate messages
- Include input validation for required fields and data types