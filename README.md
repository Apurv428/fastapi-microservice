## MICROSERVICES PROYECT WITH FASTAPI AND REDIS

 Full-stack project to practice microservices architecture. The project is a simple inventory system built with some fantastic technologies. 

The backend was developed using Python with the FastAPI framework. Each service, the Payment Service and the Inventory Service, has its own Redis database, ensuring data isolation and integrity. The frontend was crafted with React. The project consists of two separate and scalable services:

1. Payment Service: Handles the processing of product purchase orders and has its own Redis database. 💳
2. Inventory Service: Manages the products and also has its own Redis database. 📦

Each service exposes a REST API, adhering to the best practices and standards of RESTful APIs. To make it even better, each API is documented with Swagger UI, making it easy for developers to understand and use. 📚

To ensure the quality of the project, I used Jest for frontend testing and TestClient for the backend.
