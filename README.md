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



# Software Development Life-Cycle

Software Development Life Cycle is a structured process showing how software developers plan, gather requirement, design, build, test, deploy and maintain software. This allows for efficiency and effectiveness as it reduces errors while creating a quality software within budget.


### 7 Main Phases of the Life Cycle

- Planning - Determining what to build, what problem the software will solve, budget and timeline
- Requirements Gathering & Analysis - The App’s functional and non-functional requirements, e.g features, speed, performance, security.
- Design - This is where designers and developers decide the How of the software.
- Build (Development) - Developers write the actual code for frontend, backend and APIs.
- Testing - Very importantly, a test must be carried out to check for bugs, performance or security issues
- Deployment - The software is released to users which can either be a beta release, stage roll out or full production release.
- Maintenance - After launch, developers continues to improve the software, could be fixing bugs, adding new features or updating security.

### Importance of SDLC

- Develop software more efficiently
- Reduces development cost 
- Detect issues earlier
- Delivers high-quality software
- Improves user’s experience



# TCP & UDP

**TCP** (Transmission Control Protocol and **UDP** (User Data Protocol) are responsible for data delivery between applications or computers and are the two most important transport layer protocol. They both operate on the transport layer of the OSI Model.

### TCP & How it works

TCP is very reliable and connection oriented, before it sends any data, it first establishes a connection through what is called a “Three Way Hand Shake” between the sender and receiver only then can it send any data. TCP divides larger files into segments and each segments are numbered, if any data is lost in transit it retransmits again

### TCP Characteristics
- Reliable
- Connection-oriented
- Delivers an ordered data 
- Error checking
- Resend lost packets
- Flow control
- Congestion control

Applications like Email, Web browsing(HTTP, HTTPS), File Transfer, SSH, Banking, Online Shopping, Database connections use TCP.

### UDP & How it works

UDP delivers data faster option but connectionless. UDP simply sends packets without confirming if it was delivered or not. Order is also not guaranteed.

### UDP Characteristics
- Very fast
- Connectionless
- No retransmission
- No guarantee of order
- Lower overhead
- No guarantee of delivery
- No acknowledgement


Applications that use UDP includes; Video streaming, Voice calls, Online gaming, DNS queries, Live broadcast, Video conferencing.

