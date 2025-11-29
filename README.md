# foodie_restaurant
A Django-powered restaurant web app with menu management, food listings, image uploads, and admin features.
🍽️ Foodie Restaurant – Django Web Application
<p align="center"> <img src="https://img.shields.io/badge/Python-3.x-blue" /> <img src="https://img.shields.io/badge/Django-Framework-green" /> <img src="https://img.shields.io/badge/Status-Active-success" /> <img src="https://img.shields.io/badge/License-MIT-yellow" /> </p>

🍽️ Foodies – Restaurant Website (Django Project)

A full-featured restaurant website built with Django, offering menu management, user accounts, image upload, and a responsive UI.

📌 Overview

Foodies is a modern restaurant web application built to showcase dishes, manage menu items, and allow customer interaction.
It comes with a clean layout, admin management, and dynamic pages.

🛠️ Tech Stack
Component	Technology
Backend	Django (Python)
Frontend	HTML, CSS, JavaScript, Bootstrap
Database	SQLite (default)
Version Control	Git & GitHub
Media Uploads	Django File/Image Handling
✨ Features
🔹 User Authentication

Register, Login, Logout

Secure password hashing

Form validations

🔹 Restaurant Menu

Add/Edit/Delete Dishes (Admin)

Show dish images, prices, categories

Dynamic rendering using Django ORM

🔹 Image/File Upload Support

Upload food images

Display uploaded images in templates

🔹 Responsive Frontend

Mobile-friendly layouts

Static files (CSS, JS, Images) configured

🔹 Admin Dashboard

Manage menu items

Manage categories

Manage contact/reservation entries

📁 Project Structure
foodies_restaurant/
│
├── foodie_app/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│
├── media/
├── templates/
├── static/
├── manage.py
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Vanshikamahant/foodie_restaurant.git
cd foodie_restaurant

2️⃣ Create Virtual Environment
python -m venv env
env\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Apply Migrations
python manage.py migrate

5️⃣ Create Superuser
python manage.py createsuperuser

6️⃣ Run the Server
python manage.py runserver

🧪 Screenshots 
Home page
<img width="1920" height="1080" alt="Screenshot 2025-11-01 132730" src="https://github.com/user-attachments/assets/09cceaba-448a-4cef-aad7-80c1c30c8d44" />

About page
<img width="1920" height="1080" alt="Screenshot 2025-11-01 132826" src="https://github.com/user-attachments/assets/1c329a78-09e7-4f01-bc38-b9824ed5b808" />

Menu page
<img width="774" height="890" alt="Screenshot 2025-11-01 162155" src="https://github.com/user-attachments/assets/9ec3cc4a-2ebb-4448-9e54-af63323fd959" />

Book table page
<img width="1894" height="903" alt="Screenshot 2025-11-01 161910" src="https://github.com/user-attachments/assets/384bef76-ca8c-4c41-a84d-c1124cae998c" />

Feedback page
<img width="1920" height="1080" alt="Screenshot 2025-11-01 132837" src="https://github.com/user-attachments/assets/baffc1bf-a7d2-4599-a2ba-909736b9de75" />
<img width="1550" height="786" alt="Screenshot 2025-11-01 133245" src="https://github.com/user-attachments/assets/58380c3c-9290-4db1-b37b-113631c90cd8" />

Flowchart
flowchart TD

A[User Visits Website] --> B{Is User Logged In?}

B -->|No| C[Show Login / Register Page]
B -->|Yes| D[Show Homepage]

C --> C1[User Registers or Logs In]
C1 --> D

D --> E[View Menu]

E --> F{Select a Dish?}
F -->|Yes| G[View Dish Details]
F -->|No| D

G --> H{Place Reservation / Contact?}
H -->|Yes| I[Submit Form]
H -->|No| E

I --> J[Store Data in Database]
J --> K[Show Success Message]
K --> D

%% Admin Panel
A --> L[Admin Login]
L --> M[Admin Dashboard]
M --> N[Manage Menu Items: Add/Edit/Delete]
M --> O[Upload Dish Images]
M --> P[View Contact/Reservation Forms]


🚀 Future Improvements

Online food ordering

Cart & checkout system

Payment gateway

Customer reviews

User profile dashboard

🤝 Contributing

Pull requests are welcome!
For major changes, open an issue first.

📝 License

Licensed under the MIT License.

👩‍💻 Author

Vanshika Mahant
Django Developer | Python Enthusiast
GitHub: https://github.com/Vanshikamahant
