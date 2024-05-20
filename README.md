# EcoShop

EcoShop is an online store dedicated to offering a wide range of eco-friendly products. The platform provides a seamless shopping experience while promoting sustainable living. It connects environmentally conscious consumers with products that minimize environmental impact, fostering a community of eco-friendly buyers and sellers.

## Features

- Browse and search for eco-friendly products
- User registration and authentication
- User profile management
- Shopping cart and checkout process
- Order history and management
- Secure payment gateway integration

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Django, Python
- **Database:** PostgreSQL
- **Version Control:** Git
- **Deployment:** Heroku/AWS

## Project Structure

```plaintext
EcoShop/
├── ecoshop/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
│
├── apps/
│   ├── __init__.py
│   ├── products/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── forms.py
│   │   ├── templates/
│   │   │   ├── products/
│   │   │       ├── product_list.html
│   │   │       ├── product_detail.html
│   │   └── static/
│   │       ├── css/
│   │       ├── js/
│   │       ├── images/
│   │
│   ├── users/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── forms.py
│   │   ├── templates/
│   │   │   ├── registration/
│   │   │       ├── login.html
│   │   │       ├── register.html
│   │   │       ├── profile.html
│   │   └── static/
│   │       ├── css/
│   │       ├── js/
│   │       ├── images/
│   │
│   ├── orders/
│       ├── __init__.py
│       ├── admin.py
│       ├── apps.py
│       ├── models.py
│       ├── views.py
│       ├── urls.py
│       ├── forms.py
│       ├── templates/
│       │   ├── orders/
│       │       ├── cart.html
│       │       ├── checkout.html
│       └── static/
│           ├── css/
│           ├── js/
│           ├── images/
│
├── templates/
│   ├── base.html
│   ├── header.html
│   ├── footer.html
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│
├── media/
│
├── manage.py
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
