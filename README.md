<h1>Sales Management System (Django REST Framework + Vue.js)</h1>

[![Proyecto-Django.jpg](https://i.postimg.cc/y8b7jrXn/Proyecto-Django.jpg)](https://postimg.cc/pmKNXCSn)


This project is a sales management system featuring a Django backend (REST API) and a Vue.js frontend (User Interface). It enables the administration of products and categories with dynamic data visualization.

## 🚀 Technologies Used
Backend: Python, Django, Django REST Framework (DRF).

Frontend: Vue.js 3, Axios, Bootstrap 5.

Database: PostgreSQL 

Others: Django-cors-headers, Django-filter.

## 🛠️ Project Development Stages
The development was carried out following these main phases:

## Backend Configuration:

- Virtual environment creation and activation: python -m venv venv.

- Dependency installation: django, djangorestframework, django-filter, django-cors-headers.

- Definition of Data Models (Products, Categories) and Serializers to convert data into JSON.

## API Architecture:

- Implementation of Class-Based Views (Generics) and ViewSets.

- Router configuration for API URLs.

- CORS enablement to allow connection with the Vue frontend.

## Frontend Development (Vue.js):

- Vue CLI installation and app initialization.

Implementation of Axios within the onMounted hook to fetch data from the Django API.

Creation of reactive components (Navbar, Product Cards) and state management using ref and computed.

## 💻 Local Installation and Setup ##
Follow these steps to run the project on your local machine:

1. Clone the Repository
Bash
git clone https://github.com/GermanLL/ProyectoDjango.sistemaventas.git
cd ProyectoDjango.sistemaventas
2. Backend Setup (Django)
Bash
# Enter the server folder (adjust according to your structure)
cd tienda 

# Create and activate the virtual environment
python -m venv venv
# On Windows:
venv\Scripts\activate

# Install dependencies
pip install django djangorestframework django-filter django-cors-headers

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create a superuser for the admin panel
python manage.py createsuperuser

# Start the server
python manage.py runserver
The backend will be available at: http://localhost:8000/

## 3. Frontend Setup (Vue.js)
Note: Ensure you have Node.js installed.

Bash
# Open a new terminal and enter the Vue project folder
cd cliente_vue (or your frontend folder name)

# Install npm dependencies
npm install

# Run the project
npm run serve
The frontend will be available at: http://localhost:8080/

## 🔑 Access Credentials (Development Mode)
Django Admin: http://localhost:8000/admin



