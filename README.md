# Bakery Project
## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction
The Bakery Project is a web application developed using Django. It provides a platform for managing a bakery's products, allowing users to browse and purchase bakery items online.

## Features
- User authentication: Register, login, and logout functionality for users.
- Product management: Add, edit, and delete bakery products.
- Shopping cart: Add products to the cart and complete the checkout process.
- Responsive design: Optimized for various devices, including desktop and mobile.

## Technologies Used
- Django: A high-level Python web framework for rapid development.
- HTML/CSS: Frontend markup and styling.
- Bootstrap: Frontend framework for responsive design.
- JavaScript: Used for client-side interactivity.
- SQLite: Default database engine provided by Django.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/RexO77/bakery_project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bakery_project
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run migrations:
    ```bash
    python manage.py migrate
    ```
5. Start the development server:
    ```bash
    python manage.py runserver
    ```
6. Access the application at `http://localhost:8000` in your web browser.

## Usage
1. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```
2. Log in to the Django admin panel at `http://localhost:8000/admin` using the superuser credentials.
3. Manage products, users, and other site content from the admin panel.
4. Explore the frontend of the application by browsing `http://localhost:8000`.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new pull request.

## License
This project is licensed under the [MIT License](LICENSE).

---
