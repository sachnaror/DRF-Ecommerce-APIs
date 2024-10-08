
# E-commerce - Django REST API

![](https://github.com/sachnaror/DRF-Atsuko-Clone/blob/main/DRF_atsuko_clone.png)

![](https://github.com/sachnaror/DRF-Atsuko-Clone/blob/main/image.png)

## Introduction
Welcome to the Ecommerce DRF API project! This Django REST API application aims to replicate the backend functionality of [Atsuko](https://atsuko.com/), an online platform specializing in anime-inspired apparel and accessories. By building this replica, we seek to explore and implement key features and functionalities i found on the Atsuko platform.

## Project Overview
ThIS Ecommerce Replica ncompasses the development of a robust and scalable RESTful API using Django, a high-level Python web framework. Our goal is to mimic the core backend functionalities of the Atsuko platform, including user authentication, product management, shopping cart functionality, order processing, and more.

```
├──E-commerce - Django REST API/
│   ├── requirements.txt
│   ├── DRF_atsuko_clone.png
│   ├── Dockerfile
│   ├── db.sqlite3
│   ├── README.md
│   ├── docker-compose.yml
│   ├── manage.py
│   ├── image.png
│   ├── products/
│   │   ├── serializers.py
│   │   ├── apps.py
│   │   ├── permissions.py
│   │   ├── urls.py
│   │   ├── filters.py
│   │   └── views.py
│   │   ├── tests/
│   ├── core/
│   │   ├── models.py
│   │   ├── selectors.py
│   │   ├── apps.py
│   │   ├── admin.py
│   │   ├── exceptions.py
│   │   ├── manager.py
│   │   └── filters.py
│   │   ├── tests/
│   │   │   └── test_models.py
│   ├── users/
│   │   ├── signals.py
│   │   ├── tasks.py
│   │   ├── serializers.py
│   │   ├── apps.py
│   │   └── views.py
│   │   ├── tests/
│   ├── atsuko_clone/
│   │   ├── asgi.py
│   │   ├── celery.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── google_login/
│   │   ├── service.py
│   │   ├── apps.py
│   │   ├── apis.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── profiles/
│   │   ├── serializers.py
│   │   ├── apps.py
│   │   ├── permissions.py
│   │   ├── urls.py
│   │   └── views.py
│   │   ├── tests/
│   ├── notifications/
│   │   ├── signals.py
│   │   ├── tasks.py
│   │   ├── serializers.py
│   │   ├── apps.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── .idea/
│   │   ├── vcs.xml
│   │   ├── modules.xml
│   │   └── misc.xml
│   │   ├── inspectionProfiles/
│   │   │   └── profiles_settings.xml
│   ├── media/
│   │   ├── uploads/
│   │   │   ├── profile/
│   │   │   │   └── e680efe2-e6f7-4c3c-89fc-d6e63659c380.png

```

## Key Features

- **User Authentication**: Implement user registration, login, and authentication using JWT tokens.
- **Product Management**: Enable CRUD operations for managing products, including creation, retrieval, updating, and deletion.
- **Shopping Cart Functionality**: Allow users to add products to their shopping carts, modify quantities, and proceed to checkout.
- **Order Processing**: Enable users to place orders, view order history, and manage order status.
- **Search and Filtering**: Implement search and filtering functionalities to allow users to find products based on various criteria.
- **Admin Panel**: Provide an admin interface for managing users, products, orders, and other backend functionalities.

## Technologies Used
- **Django**: High-level Python web framework for backend development.
- **Django REST Framework (DRF)**: Powerful toolkit for building Web APIs in Django.
- **JWT Authentication**: Secure user authentication using JSON Web Tokens.
- **PostgreSQL**: Relational database management system for data storage.
- **Docker**: Containerization platform for easy deployment and scalability.
- **Swagger/OpenAPI**: API documentation and testing tool for better API management.

## Getting Started
To get started with the Atsuko Replica project, follow the steps outlined in the installation guide below. You can then explore the API endpoints using tools like Swagger or Postman.

## Installation Guide

# Atsuko Clone - Installation Guide

Thank you for your interest in the Atsuko Replica project! Follow the steps below to set up the project environment and get started with development.

## Prerequisites
Before you begin, ensure that you have the following prerequisites installed on your system:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation Steps
1. **Clone the Repository**:
   Clone the Atsuko Replica repository to your local machine using the following command:
   ```
   git clone https://github.com/sachnaror/DRF_atsuko_clone.git
   ```

2. **Navigate to the Project Directory**:
   ```
   cd DRF_atsuko_clone
   ```

3. **Start Docker Containers**:
   Run the following command to build and start the Docker containers:
   ```
   docker-compose up
   ```

4. **Access the API Documentation**:
   Once the Docker containers are running, you can access the API documentation at:
   ```
   http://localhost:8000/swagger/
   ```

## Usage
After setting up the project, you can explore the API endpoints and interact with the Atsuko Replica API using tools like Swagger or Postman.

## Shutting Down
To stop the Docker containers and shut down the project, press `Ctrl + C` in the terminal where `docker-compose up` is running. Then, run the following command to remove the containers:
   ```
   docker-compose down
   ```

---

Feel free to customize this installation guide to include any additional information specific to your project or environment.


## Acknowledgements
Special thanks to the team at Atsuko for inspiring this project and providing valuable insights into e-commerce platform development.

---

Feel free to customize and expand upon this project description as needed!
