# 🍽️ Recipe Finder – Django REST API

A full-stack recipe management web application built with Django and Django REST Framework.  
This project allows users to sign up, log in, and manage recipes with image upload functionality and token-based authentication.

---

## 🚀 Features

- User registration and login
- Token-based authentication
- Create, update, delete recipes
- Upload recipe images
- Django Admin dashboard
- RESTful API endpoints
- SQLite database integration

---

## 🛠️ Tech Stack

- Python 3.11
- Django
- Django REST Framework
- SQLite
- Pillow (for image handling)
- HTML / CSS (if templates are used)

---

## 📂 Project Structure

recipe-finder-django-api/
│
├── recipes/ # Main app
├── recipe_finder_django/ # Project settings
├── manage.py
├── requirements.txt
└── .gitignore


---

## ⚙️ Installation & Setup

1. Clone the repository:

git clone https://github.com/Omnia9789/recipe-finder-django-api.git


2. Navigate into the project directory:

cd recipe-finder-django-api


3. Create a virtual environment:

python -m venv venv


4. Activate the virtual environment:

**Windows:**
venv\Scripts\activate


5. Install dependencies:

pip install -r requirements.txt


6. Apply migrations:

python manage.py migrate


7. Run the development server:

python manage.py runserver


Visit:
http://127.0.0.1:8000/


---

## 🔐 Authentication

This project uses token-based authentication.

After login via API:
- A token is generated
- The token must be included in request headers for protected routes

Example header:

Authorization: Token your_token_here


---

## 📡 API Endpoints

| Method | Endpoint        | Description |
|--------|-----------------|-------------|
| POST   | /api/signup/    | Register new user |
| POST   | /api/login/     | Login and receive token |
| GET    | /api/recipes/   | List recipes |
| POST   | /api/recipes/   | Create recipe |
| PUT    | /api/recipes/<id>/ | Update recipe |
| DELETE | /api/recipes/<id>/ | Delete recipe |

---

## 📸 Screenshots

*(Add your screenshots inside a folder named `screenshots/` and link them below)*

### Homepage
![Homepage](screenshots/home.png)

### Recipe List
![Recipe List](screenshots/recipe-list.png)

### Admin Panel
![Admin Panel](screenshots/admin-panel.png)

---

## 📌 Future Improvements

- Add search functionality
- Add favorites feature
- Improve UI/UX design
- Deploy to cloud platform (Render / Railway)
- Add pagination & filtering

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

Omnia Ali  
GitHub: https://github.com/Omnia9789
