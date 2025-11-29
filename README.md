# foodie_restaurant
A Django-powered restaurant web app with menu management, food listings, image uploads, and admin features.
🍽️ Foodie Restaurant – Django Web Application
<p align="center"> <img src="https://img.shields.io/badge/Python-3.x-blue" /> <img src="https://img.shields.io/badge/Django-Framework-green" /> <img src="https://img.shields.io/badge/Status-Active-success" /> <img src="https://img.shields.io/badge/License-MIT-yellow" /> </p>

Foodie Restaurant is a full-featured Django web application designed for restaurant management.
It allows users to view menu items, upload images, manage food categories, authenticate, and handle simple orders.
The frontend is built using HTML, CSS, and Bootstrap, ensuring a clean and responsive user interface.

⭐ Features
Category	Description
🔐 Authentication	User signup, login & logout
🍔 Menu System	Add, edit, delete food items
🖼️ Image Uploads	Upload dish images using Django Media
🛒 Orders (Optional)	Add to cart, checkout summary
🛠️ Admin Management	Manage menu, categories, users
📱 Responsive UI	Built with Bootstrap
🗂️ Database	SQLite (default)
🛠️ Tech Stack

Python 3

Django Framework

HTML5, CSS3, Bootstrap

SQLite Database

Git & GitHub

VS Code

📁 Project Structure
foodie_restaurant/
│── foodie_restaurant/        # Main Django project (settings, URLs)
│── app/                      # Django application
│── templates/                # HTML templates
│── static/                   # CSS, JS, Images
│── media/                    # Uploaded images
│── requirements.txt          # Python dependencies
│── db.sqlite3                # Database
│── manage.py

🚀 Run This Project Locally
1. Clone the repository
git clone https://github.com/Vanshikamahant/foodie_restaurant.git

2. Navigate into the project folder
cd foodie_restaurant

3. Create virtual environment
python -m venv env

4. Activate environment

Windows

env\Scripts\activate


Mac/Linux

source env/bin/activate

5. Install dependencies
pip install -r requirements.txt

6. Apply database migrations
python manage.py migrate

7. Start the development server
python manage.py runserver


🔗 Open in browser:

http://127.0.0.1:8000/

🔐 Admin Panel

Create superuser:

python manage.py createsuperuser


Admin login page:

http://127.0.0.1:8000/admin/

📸 Screenshots (Add Your Images)

You can place screenshots inside a screenshots/ folder and reference them:

![Home Page](screenshots/home.png)
![Menu Page](screenshots/menu.png)
![Admin Panel](screenshots/admin.png)

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch (feature-branch)

Commit your changes

Push your branch

Open a Pull Request

📜 License
MIT © 2025 Vanshika Mahant

👩‍💻 Author

Vanshika Mahant
Django Developer | Python Enthusiast
GitHub: https://github.com/Vanshikamahant
