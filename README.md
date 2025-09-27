# Django Hello World App

A simple Django application that displays "Hello World!" on the homepage.

## Project Structure

```
mysite/
├── manage.py              # Django management script
├── mysite/                # Main project directory
│   ├── __init__.py
│   ├── settings.py        # Django settings
│   ├── urls.py           # URL configuration
│   ├── wsgi.py           # WSGI configuration
│   └── asgi.py           # ASGI configuration
└── README.md             # This file
```

## Features

- Simple "Hello World!" homepage
- Django admin interface available at `/admin/`
- SQLite database (default Django setup)

## Getting Started

### Prerequisites

- Python 3.x
- Django 5.2.6 (or compatible version)

### Installation

1. Clone or download this project
2. Navigate to the project directory:
   ```bash
   cd mysite
   ```

3. Install Django (if not already installed):
   ```bash
   pip install django
   ```

### Running the Application

1. Start the Django development server:
   ```bash
   python manage.py runserver
   ```

2. Open your web browser and navigate to:
   ```
   http://127.0.0.1:8000/
   ```

3. You should see "Hello World!" displayed on the page.

### Accessing the Admin Interface

- Navigate to `http://127.0.0.1:8000/admin/` to access the Django admin interface
- You'll need to create a superuser account first:
  ```bash
  python manage.py createsuperuser
  ```

## Development

This is a basic Django project structure. You can extend it by:

- Creating Django apps using `python manage.py startapp <app_name>`
- Adding more views and URL patterns
- Creating models for database functionality
- Adding templates for more complex HTML pages

## License

This project is open source and available under the MIT License.
