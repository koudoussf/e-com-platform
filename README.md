# 📝 ECOM-PLATFORM

This project was completed as part of my learning of the Django framework.

## main features

-   Catalog views for browsing products\
-   Shopping cart stored using Django sessions\
-   Customer order registration and management\
-   Background workers with message queues and brokers\
-   Payment gateway integration with Stripe\
-   Orders export in CSV format\
-   Coupon system
-   recommendation engine with Redis 

## Technologies used

-   Python / Django\
-   HTML / CSS / JS\
-   Celery \
-   RabbitMQ \
-   Redis \

## Installation

### 1. Clone the repository

``` bash
git clone https://github.com/koudoussf/e-com-platform.git
cd myshop/
```

### 2. Create the virtual environment

``` bash
python -m venv venv
source venv/bin/activate
```

### 3. Install the dependencies

``` bash
pip install -r requirements.txt
```

### 4. Apply the migrations

``` bash
python manage.py migrate
```

### 5. Start the server

``` bash
python manage.py runserver
```

## Project structure 

    myshop/
    ├── cart/
    ├── coupons/
    ├── myshop/
    ├── orders/
    ├── payment
    ├── shop/
    ├── static/
    ├── manage.py
    └── requirements.txt

## 📋 To-Do List

### 🎯 Fonctionnalités

-   [ ] Add "about"
-   [ ] Add internationalization
-   [ ] Add contact form
-   [ ] Authentification

### UI / Frontend
-   [ ] Optimise image

### Backend

-   [ ] Add unit test

### Deployment

-   [ ] Prepare Dockerfile
-   [ ] Set CI/CD

