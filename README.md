# Simple E-Commerce Store

A simple e-commerce web application built with **Python and Django** as part of Internship Task 1.

## Features

- Product listing
- Product detail page
- Product images
- Shopping cart
- Increase/decrease cart quantity
- Remove items from cart
- User registration
- User login/logout
- Checkout
- Order processing
- Order status management
- Django Admin
- SQLite database
- CSS styling with reusable base template

## Technologies

- Python
- Django
- HTML5
- CSS3
- SQLite
- Pillow
- Django Authentication
- Django Sessions

## Project Structure

```text
Ecommerce_internship/
├── ecommerce/
├── store/
│   ├── migrations/
│   ├── templates/store/
│   ├── static/store/css/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── media/
├── db.sqlite3
├── manage.py
└── venv/
```

## Setup

### 1. Open the project

```text
E:\Ecommerce_internship
```

### 2. Activate virtual environment

Windows PowerShell:

```powershell
.\venv\Scripts\activate
```

### 3. Install dependencies

```powershell
pip install django pillow
```

### 4. Apply migrations

```powershell
python manage.py migrate
```

### 5. Start the server

```powershell
python manage.py runserver
```

### 6. Open the application

http://127.0.0.1:8000/

## Admin Panel

Create a superuser:

```powershell
python manage.py createsuperuser
```

Open:

http://127.0.0.1:8000/admin/

The admin panel can be used to manage products and orders.

## Application Flow

```text
Register
   ↓
Login
   ↓
Browse Products
   ↓
View Product
   ↓
Add to Cart
   ↓
Manage Cart
   ↓
Checkout
   ↓
Place Order
   ↓
Order Success
```

## Database

The project uses SQLite. The database file is:

```text
db.sqlite3
```

Main models:

- Product
- Order
- OrderItem

## Running the Project Again

After closing VS Code:

1. Open `E:\Ecommerce_internship` in VS Code.
2. Open a new terminal.
3. Activate the virtual environment:

```powershell
.\venv\Scripts\activate
```

4. Start Django:

```powershell
python manage.py runserver
```

5. Open:

http://127.0.0.1:8000/

Closing VS Code does not delete the project or database.

## Testing Checklist

- [x] Product listing
- [x] Product details
- [x] Shopping cart
- [x] Quantity management
- [x] Remove from cart
- [x] Registration
- [x] Login/logout
- [x] Checkout
- [x] Order processing
- [x] Admin order management
- [x] CSS styling

## Future Enhancements

- Payment gateway
- Product search and filtering
- Wishlist
- Order history
- Email notifications
- Product reviews
- Advanced inventory management
- Production deployment

## Author

**Abinesh Manikandan**

MCA Graduate
