# Dukkan-Ecommerce-Website 

An eCommerce platform developed using HTML5, CSS3, Python (Django), and SQLite.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This eCommerce project is designed to provide a seamless online shopping experience. It includes various features that enhance the user experience, such as filtering products, searching for items, and managing a list of favorite products. This project was developed as a group effort.

## Features

- **User Authentication and Authorization**: Secure login and registration system with user roles.
- **Product Catalog with Categories**: Products are organized into categories for easy browsing.
- **Shopping Cart Functionality**: Users can add products to their cart and proceed to checkout.
- **Order Management**: Users can view their past orders and order details.
- **Payment Gateway Integration**: Secure payment processing using a mock payment gateway.
- **Search Functionality**: Users can search for products by name, description, or category.
- **Filter Feature**: Products can be filtered based on various criteria such as price, category, and ratings.
- **Favorite Feature**: Users can add products to a list of favorites for easy access later.
- **Responsive Design**: The application is fully responsive and works well on all devices.
- **Admin Panel**: Admins can manage products, categories, orders, and users from a dedicated admin panel.

## Technologies Used

- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript (with libraries like jQuery and Bootstrap)
- **Backend**: 
  - Python
  - Django
- **Database**: 
  - SQLite (using Django ORM)
- **Other Tools**: 
  - Git for version control

## Setup Instructions

To set up and run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/sanskratipatel/Dukkan-Ecommerce-Website.git
    cd your-repository
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Create a superuser**:
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

7. **Access the application**:
    Open your browser and go to `http://localhost:8000/`

## Usage

### Browsing Products

- **Search**: Use the search bar at the top of the page to find products by name, description, or category.
- **Filter**: Use the filter options on the sidebar to narrow down products based on price range, category, and ratings.
- **Favorites**: Click the heart icon on any product to add it to your list of favorites for quick access later.

### Shopping Cart and Checkout

- **Add to Cart**: Click the "Add to Cart" button on any product page to add it to your shopping cart.
- **View Cart**: Click the cart icon in the header to view the items in your cart.
- **Checkout**: Proceed to checkout from the cart page, fill in your details, and complete the purchase.

### Order Management

- **Order History**: View your past orders from the user dashboard.
- **Order Details**: Click on any order to view detailed information about it.

## Contributing

We welcome contributions to improve this project. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

