# E-commerce Site using Django Framework

This Full-Fledged E-commerce Site is an advanced project developed using Django Framework, HTML, and CSS. The project includes all the functionalities that any top-tier e-commerce site would claim to have. It also has beautiful UI designs with advanced back-end development using Python Django.

The website provides features such as searching for every item in the e-commerce store, login/registering, adding items to the cart, editing/adding/deleting items from the cart, making payments which include the shipping address and card-payment systems, and most importantly, it also has a feature to track anyone’s order from the order – delivery process.

## System Overview
The system is built entirely in Django Framework in the back end and HTML, and CSS in the front end. It has a full-featured user interface with all the functionalities of any e-commerce website. It also provides a separate dashboard for the admin to track and control all activities, including products, orders, feedback, and customer registration into the system.

## How to run the Project
To run this project, you must have Python installed on your PC. After downloading the project, follow the steps below:

1. Extract/unzip the file

2. Go inside the project folder, open the command prompt (Windows) or terminal (macOS/Linux), and type the following commands to install Django Framework and run the web server:

```pip install -r requirements.txt```

```python manage.py runserver```

3. Finally, open the browser and go to: `localhost:8000`

For admin panel:

- Username: admin
- Password: admin

## Project Structure
The project follows a standard Django application structure, with the main components being:

- accounts: Handles user authentication and registration.
- cart: Handles adding, editing, and removing items from the shopping cart.
- checkout: Handles payment processing and order placement.
- core: Contains the main website views and templates.
- orders: Handles order management and tracking.
- products: Handles product listings and details.
