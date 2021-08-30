# Best Buy Backend

![Lines of code](https://img.shields.io/tokei/lines/github/varunjha/Best-Buy-Backend?style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/varunjha/Best-Buy-Backend)
![Twitter Follow](https://img.shields.io/twitter/follow/varunjha089?style=flat)
![GitHub language count](https://img.shields.io/github/languages/count/varunjha/Best-Buy-Backend)
![GitHub top language](https://img.shields.io/github/languages/top/varunjha/Best-Buy-Backend)

This code is the backend portion of a shopping application for college project.

[comment]: <> (## Screenshots)

[comment]: <> (![App Screenshot]&#40;https://via.placeholder.com/468x300?text=App+Screenshot+Here&#41;)

## Tech Stack

**Client:** `React`

**Server:** `Django Rest-API`

**Database:** `PostgreSQL`

**API:** `Django REST framework`

## Requirements

REST framework requires the following:

- Python (3.5, 3.6, 3.7, 3.8, 3.9)
- Django (2.2, 3.0, 3.1)

## Installation

```colsole
ubuntu@ip:~$ git clone https://github.com/varunjha/Best-Buy-Backend.git

(venv) ubuntu@ip:~$ pip install requirements.txt

(venv) ubuntu@ip:~$ python manage.py makemigrations

(venv) ubuntu@ip:~$ python manage.py migrate

(venv) ubuntu@ip:~$ python manage.py runserver
```

## Methods

As we are using **Django Rest-API** to connect between **Frontend** and **Backend**, so several methods which are 
being used as follows:

| Methods | Routes |
|---|---|
| **GET** | **/api/products** |
| **GET** | **/api/products/11** |
| **POST** | **/api/products/create** |
| **PUT** | **/api/products/update/15** |
| **DELETE** | **/api/products/delete/15** |

## Features

- Product
    - 5-Star rating system
    - User can give their feedback

- User Account
    - Authentication
    - Modify Order
    - View Order
    - Create Order
    - Add feedback to product
    - Look for Previous Orders and Re-Order Them

- Admin Account
    - Admin Panel
    - Add Product
    - Update Product Quantity
    - View Orders
    - Send Promotion Message
    - Pin the Feedback

- Shopping Cart

- Search Product

- Payment Integration
    - PayPal
    - Stripe

- Sending **E-Mail**.
    - Confirming Account
    - Order Successful Message
    - Promotion Message

## Command we have used

For **`Back-End`**

```console
(venv) ubuntu@ip:~$ pip install djangorestframework

(venv) ubuntu@ip:~$ pip install markdown       # Markdown support for the browsable API.

(venv) ubuntu@ip:~$ 

(venv) ubuntu@ip:~$ 

```
