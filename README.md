# 🛒 Online Shopping Cart Web Application

## About the Project

The Online Shopping Cart is a Java-based e-commerce web application that allows users to browse products, manage their shopping cart, and place orders through a simple web interface.

This project demonstrates Java web technologies, database connectivity, and server-side application development.

## Technologies Used

* Java
* HTML, CSS, JavaScript
* JSP
* Java Servlets
* JDBC
* MySQL
* Apache Tomcat 9
* Maven

## Features

* User Registration and Login
* View Available Products
* Add Products to Shopping Cart
* Increase or Decrease Product Quantity
* Remove Products from Cart
* Checkout Process
* Place Orders
* Store Order and Transaction Information in MySQL

## Project Structure

```text
Shopping-Cart/
├── databases/
├── src/
├── WebContent/
├── pom.xml
└── README.md
```

## Database Configuration

The application uses MySQL to store user, product, cart, order, and transaction information.

Update `application.properties` with your database credentials:

```properties
db.driverName = com.mysql.cj.jdbc.Driver
db.connectionString = jdbc:mysql://localhost:3306/shopping-cart
db.username = YOUR_MYSQL_USERNAME
db.password = YOUR_MYSQL_PASSWORD
```

## Prerequisites

* Java JDK
* MySQL Server
* Apache Tomcat 9
* Maven

## How to Run

1. Clone or download the repository.
2. Set up the MySQL database.
3. Import the SQL script from the database folder.
4. Configure database credentials.
5. Deploy the WAR file to Apache Tomcat 9.
6. Start MySQL and Tomcat.
7. Open the application in your browser.

Application URL:

```text
http://localhost:8080/shopping-cart-0.0.1-SNAPSHOT/
```

## Payment Information

The current checkout flow uses a demo payment process. It is not connected to a real payment gateway. Do not enter real card details.

## Current Limitations

* Real payment gateway integration is not available.
* Order cancellation and product return are not implemented.

## Future Enhancements

* Secure payment gateway integration.
* Order cancellation functionality.
* Product return functionality.
* Product search and filtering.
* Improved security and validation.

## Learning Outcomes

* Understanding Java Servlets and JSP.
* JDBC connectivity with MySQL.
* Database operations and CRUD.
* Session management.
* Shopping cart management.
* Order processing.
* Deploying Java web applications using Apache Tomcat.

## Project Attribution

This repository is based on an existing open-source Java shopping cart project and is used for learning, setup, and understanding Java web application development.
