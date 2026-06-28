# fastapi-pydantic-demo

A simple REST API built with **FastAPI** and **Pydantic** to demonstrate the fundamentals of RESTful API development in Python. This project manages an in-memory list of products and showcases how to define data models, create API endpoints, and perform basic CRUD operations.

## 📌 Features

* Create a FastAPI application
* Define request and response models using **Pydantic**
* Retrieve all products
* Retrieve a product by its ID
* Add new products to the inventory
* Automatic request validation
* Interactive API documentation with Swagger UI

## 🛠️ Tech Stack

* Python
* FastAPI
* Pydantic
* Uvicorn

## 📂 Project Structure

```
.
├── main.py        # FastAPI application and API endpoints
├── models.py      # Pydantic Product model
└── README.md
```

## 📚 API Endpoints

| Method | Endpoint                 | Description                  |
| ------ | ------------------------ | ---------------------------- |
| GET    | `/`                      | Welcome endpoint             |
| GET    | `/products/`             | Retrieve all products        |
| GET    | `/products/{product_id}` | Retrieve a product by its ID |
| POST   | `/products/`             | Create a new product         |

## ▶️ Running the Project

1. Install the required packages:

```bash
pip install fastapi uvicorn
```

2. Start the development server:

```bash
uvicorn main:app --reload
```

3. Open your browser:

* Swagger UI: `http://127.0.0.1:8000/docs`
* ReDoc: `http://127.0.0.1:8000/redoc`

## 📖 What we have Learnt

* Building REST APIs with FastAPI
* Creating data models using Pydantic
* Path parameters
* POST request handling
* Request body validation
* Returning JSON responses
* Working with an in-memory data store



