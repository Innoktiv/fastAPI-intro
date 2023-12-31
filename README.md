# fastAPI-intro

![FastAPI Logo](https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png)

This is a simple example of a FastAPI application. FastAPI is a modern, fast, web framework for building APIs with Python 3.7+ based on standard Python type hints.

## Features

- Fast and asynchronous.
- Automatic interactive documentation with Swagger UI and ReDoc.
- Easy data validation and serialization with Pydantic.
- RESTful routing and support for WebSockets.
- Dependency injection, security, and more.

## Getting Started

### Prerequisites

Before you start, ensure you have Python 3.7+ installed.

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/innoktive/fastAPI-intro
   cd fastAPI-intro


### Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

### install proyect dependencies
pip install -r requirements.txt

### Run the fastAPI application
uvicorn main:app --reload

The API will be available at http://localhost:8000.

API Endpoints
/items/: GET - List all items.
/items/{item_id}/: GET - Retrieve an item by ID.
/items/: POST - Create a new item.
/items/{item_id}/: PUT - Update an item.
/items/{item_id}/: DELETE - Delete an item.
Interactive Documentation
FastAPI generates interactive documentation that you can access at http://localhost:8000/docs. Explore the API and try out different endpoints using the Swagger UI.

Contributing
Feel free to contribute to this project. You can open issues, create pull requests, or suggest improvements.

License
This project is open-source and available under the MIT License.

Acknowledgments
FastAPI - The amazing web framework used in this project.
Pydantic - Data validation and serialization library.
uvicorn - ASGI server for running FastAPI.
Happy coding!




Please make sure to replace `yourusername` in the repository URL and customize the content as needed. You should also include your actual code and modify the instructions for setup and usage based on your project's structure.

