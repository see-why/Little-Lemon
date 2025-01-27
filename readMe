# Little Lemon Restaurant Website

A full-stack Django web application for a Mediterranean restaurant that allows customers to browse the menu, make table reservations, and view booking information.

## Features

- View restaurant menu items and details
- Make table reservations for specific dates and time slots
- View all current reservations
- Responsive design for mobile and desktop
- Admin interface for restaurant management

## Tech Stack

- Python 3.9
- Django 4.1
- MySQL Database
- HTML/CSS/JavaScript
- Bootstrap for styling

## Installation

1. Clone the repository:
```sh
git clone <repository-url>
cd littlelemon
```

2. Install dependencies using Pipenv:
```sh
pipenv install
```

3. Create MySQL database:
```sql
CREATE DATABASE reservations;
```

4. Configure environment variables in `.env`:
```
DB_USER='admindjango'
DB_PASSWORD='employee@123!'
```

5. Run migrations:
```sh
python manage.py migrate
```

6. Start development server:
```sh
python manage.py runserver
```

## Project Structure

- [`littlelemon/settings.py`](littlelemon/settings.py) - Main project settings
- [`restaurant/models.py`](restaurant/models.py) - Database models
- [`restaurant/views.py`](restaurant/views.py) - View logic
- [`restaurant/urls.py`](restaurant/urls.py) - URL routing
- [`restaurant/templates/`](restaurant/templates/) - HTML templates
- [`restaurant/static/`](restaurant/static/) - Static assets

## Models

- [`Menu`](restaurant/models.py) - Restaurant menu items
- [`Booking`](restaurant/models.py) - Table reservations

## URLs

- `/` - Homepage
- `/menu/` - Restaurant menu
- `/book/` - Make reservation
- `/reservations/` - View reservations
- `/admin/` - Admin interface

## Contributing

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## License

This project is licensed under the MIT License.
