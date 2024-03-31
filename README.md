# Mobile_Shopping e-Commerce-Website

Welcome to my Online Mobile Shopping app! This application is built using PHP and MySQL, allowing users to browse through a selection of mobile devices, add them to their carts, and make purchases. The shopping cart information is stored in a MySQL database for seamless user experience.

## Features :-

1. Browse Mobiles: View a list of available mobile devices with details such as name, description, and price.
2. Add to Cart: Easily add mobile devices to your shopping cart.
3. View Cart: Check the items in your cart with quantity and total price.
4. Checkout: Complete the purchase by providing necessary details.
5. Database Storage: All product and cart information is stored in a MySQL database for persistence.

## Requirements :-

1. PHP 7.0 or higher
2. MySQL database
3. Web server (e.g., Apache, Nginx)

## Installation :-

1. Clone the Repository :

```bash
git clone https://github.com/anamika4ak/mobile-shopping-app.git
```

2. Navigate to the Project's directory :

```bash
cd mobile-shopping-app
```

3. Configure your web server to point to the project directory.

## Database Setup :-

1. Create a MySQL database for the application.

2. Import the database schema using the provided SQL file (shopee.sql):

```bash
mysql -u your-username -p your-database-name < shopee.sql
```

3. Update the database configuration in config.php:

```bash
    protected $host = 'your-host';
    protected $user = 'your-username';
    protected $password = 'your-password';
    protected $database = "your-database-name";
```

## Usage :-

1. Access the application through your web browser.

2. Browse through the mobile devices, add them to your cart, and proceed to checkout.

3. Complete the purchase by providing the required information.

4. Explore the admin panel (if available) for managing products and orders.
