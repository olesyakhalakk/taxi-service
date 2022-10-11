# Taxi Service

**The goal of this project is to create a taxi service.
The project implements driver authentication with different functionality. 
To use all features you need to create new driver and log in, after that you can:**

* **_create new car/manufacturer_** 
* **_display all drivers/cars/cars by driver/manufacturers_**
* **_add driver to car._**

## Implementation details and technologies

**Project based on 3-layer architecture:**
* **_Presentation layer (controllers)_**
* **_Application layer (services)_**
* **_Data access layer (DAO)_**


## Technologies
* Apache Tomcat - version 9.0.65
* MySQL - version 8.0.22
* JDBC
* Servlet
* JSTL
* JSP
* HTML, CSS

## Setup
1. Clone this project
2. Configure Tomcat Server
3. Install MySQL RDBMS and MySQL Workbench on your computer
4. Use script from src/main/resources/init_db.sql to configure MySQL
5. Insert your own MySQL username and login in dbProperties in the ConnectionUtil class.

   _USERNAME: "root"_

   _PASSWORD: "1234"_

   _URL: jdbc:mysql://localhost:3306/taxi , where:_

   _localhost - host name,_

   _3306 - port,_

   _taxi - database name._

6. Run project