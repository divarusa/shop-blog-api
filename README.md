# Shop & Blog REST API

REST API built with Django REST Framework: shop, blog, user registration and authentication.

## Features

- User registration and authentication with code confirmation
- Products: create, read, update, delete
- Blog: posts and comments
- Class-based views
- PostgreSQL database and Docker setup

## Tech Stack

- Python 3
- Django
- Django REST Framework
- PostgreSQL
- Docker, Docker Compose

## Getting Started

1. Clone the repository:
git clone https://github.com/divarusa/shop-blog-api.git
cd shop-blog-api2. Create a .env file in the project root:
SECRET_KEY=your-secret-key
DB_NAME=your-db-name
DB_USER=your-db-user
DB_PASSWORD=your-db-password3. Build and run:
docker-compose up --buildThe API will be available at http://localhost:8000/.

## Project Structure

- blog — blog posts and comments
- product — products
- users — registration and authentication
- shop_api — project settings
