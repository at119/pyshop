# PyShop

## Overview

PyShop is a web-based e-commerce application developed using Python and Django.

The project was created to practice backend web development and understand how an online shopping platform works, including product management, shopping cart functionality, and handling data through a web application.

## Project Goals

The main goals of PyShop are to:

* Build a functional e-commerce website using Django
* Practice Python backend development
* Work with databases and Django models
* Create dynamic web pages
* Implement product management
* Understand the structure of a Django web application

## Features

The application includes functionality for:

* Viewing products
* Displaying product information
* Managing products
* Adding products to a shopping cart
* Managing shopping cart items
* Working with product categories
* Connecting the application to a database
* Rendering dynamic pages using Django templates

## Technologies

* Python
* Django
* HTML
* CSS
* SQLite
* Django Templates

## Project Structure

The project follows the standard Django application structure, separating the main project configuration from the application logic.

Key components include:

* **Models** — Define and manage application data
* **Views** — Handle application logic and requests
* **Templates** — Provide the user interface
* **URLs** — Define application routes
* **Database** — Stores products and other application data

## How It Works

The application follows the typical Django request-response structure:

1. A user opens a page in the browser.
2. Django receives the request through the configured URL.
3. The corresponding view processes the request.
4. The view interacts with the database when necessary.
5. Django renders the appropriate template.
6. The resulting page is displayed to the user.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/pyshop.git
cd pyshop
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the development server:

```bash
python manage.py runserver
```

Then open the local development server in your browser.

## Learning Outcomes

Through this project, I practiced:

* Python and Django development
* Backend application structure
* Database integration
* Django models and views
* URL routing
* Templates
* CRUD operations
* Building a web application from scratch

## Author

**Amina Tynybekova**
