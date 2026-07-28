# LAMP-SDLC-TCP-UDP
A  collection of report covering LAMP-SDLC-TCP-UDP


LAMP Stack is a collection of software products and programming languages used to build and run a web or mobile applications.
LAMP stands for ( LINUX, APACHE, MYSQL, PHP).
It is one of the oldest and most widely used tech stack.

- Linux - This is the operating system running (think of it as the foundation of a house) on the server. It manages the hardware, controls the memory, organises files, provides security and handles networking.
- Apache - Apache is the web server (think of it as an office receptionist) and it decides which website was requested, which files are needed, whether PHP code should be executed or if a static file should simply be returned. It listens on Port 80 (HTTP) & Port 443 (HTTPS).
- MySQL - This is the Database (think of it as a huge digital filing cabinet). It stores information of users, products, orders, payments, reviews and shopping carts.
- PHP - PHP is the programming language. It contains the logic of the application. It performs tasks such as logging in users, registering new accounts, processing payments, calculating prices, sending emails, validating forms and uploading files. 

## Application Request Flow Step by Step

Let's assume a client visits https://www.myshop.com/products

1. Browser sends request
3. Apache receives request
4. Apache detects “products.php”
5. Apache sends request to PHP
6. PHP executes code
7. PHP asks MySQL “ SELECT * FROM PRODUCTS”
8. MySQL returns product data
9. PHP creates HTML
10. Apache sends webpage
11. Browser displays products










