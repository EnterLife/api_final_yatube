# Description
"api_final_yatube
" is a tutorial project on the example of creating an API for the fictional project "Yatube".

# Installation
### 1. Clone the repository
### 2. Create and activate virtual environment for the project
    python -m venv venv

    source venv/scripts/activate

### 3. Install dependencies
    python pip install -r requirements.txt

### 4. Make migrations
    python manage.py makemigrations

    python manage.py migrate

### 5. Run the server
    python manage.py runserver

### 6. Read the doc
    http://localhost:8000/redoc/