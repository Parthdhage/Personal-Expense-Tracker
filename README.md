# Personal Expense Tracker

A PHP and MySQL application for recording expenses and reviewing spending by date and category.

## Features

- User registration, login, and profile management
- Add and manage expense records
- View expense reports across daily, monthly, and yearly periods
- Store application data in MySQL

## Repository layout

    index.php                 Application entry point
    register.php              Account registration
    login.php                 Authentication
    add_expense.php           Expense entry
    manage_expense.php        Expense management
    expensereport.php         Expense reporting
    PersonalExpenseTracker.sql Database schema and seed data
    css/                      Stylesheets and frontend libraries
    js/                       Browser-side scripts

## Run locally

Prerequisites: PHP, MySQL, and a local web server. XAMPP is one option.

1. Start Apache and MySQL.
2. Create a MySQL database and import PersonalExpenseTracker.sql using phpMyAdmin or the MySQL command line.
3. Set the local database connection values in config.php.
4. Place the repository under the web server's document root.
5. Open the project URL in a browser.

Use local credentials that you control. Do not publish passwords, database credentials, or sample user credentials in documentation.

## License

See LICENSE.md for the license supplied with this repository.
