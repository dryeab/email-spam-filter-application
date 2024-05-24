# Email Spam Filter Application - Backend

Welcome to the backend of the Email Spam Filter Application. This guide will help you set up and run the backend server using Django.

## Prerequisites

Ensure you have the following installed on your system:

- Python 3.x
- pip (Python package installer)
- virtualenv (optional but recommended)

## Setup Instructions

Follow these steps to set up and run the backend server:

### 1. Create a Virtual Environment

A virtual environment helps to manage dependencies and avoid conflicts with other projects.

```bash
python -m venv venv
```

### 2. Activate the Virtual Environment

Activate the virtual environment to start using its isolated environment.

On macOS/Linux:

```bash
source venv/bin/activate
```

On Windows:
```bash
venv\Scripts\activate
```

### 3. Install Dependencies

Install all necessary packages listed in the requirements.txt file.

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
Apply database migrations to set up the database schema.

```bash
python manage.py migrate
```

### 5. Run the Server
Start the development server.

```bash
python manage.py runserver
```