
# SpendWise

SpendWise is a personal expense tracker built with Django
and PostgreSQL.

## Features

[//]: # (- User registration and authentication)

[//]: # (- Create, view, edit, and delete transactions)

[//]: # (- Categorize income and expenses)

[//]: # (- Filter transactions by date and category)

[//]: # (- View monthly financial summaries)

## Tech stack

- Python
- Django
- PostgreSQL
- HTML, CSS, Bootstrap
- pytest or Django TestCase

## Getting started

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd spendwise
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

Activate it using the command for your operating system.

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure environment variables

Copy `.env.example` to `.env` and fill in your local settings.

Create a PostgreSQL database and user according to your
local configuration.

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Create an administrator

```bash
python manage.py createsuperuser
```

### 7. Start the development server

```bash
python manage.py runserver
```

## Project status

Work in progress.

## License

Add a license if you intend to distribute the project.
