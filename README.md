# Taxi Service

**This is fully functioning taxi service, that allows user to manage taxi station.
For example adding new cars, drivers, manufacturers etc.
It uses Java Servlet Pages technology to display needful information and interact with user.
All functionality and technologies are described below.**

## Functionality list:
* **_Authorization and authentication of user (Driver)_**
* **_Adding new driver (registration)_**
* **_Create manufacturers_**
* **_Create cars_**
* **_Add drivers to car_**
* **_Delete cars/drivers/manufacturers_**
* **_Delete drivers from car_**

## Implementation details and technologies

**Project based on 3-layer architecture:**
* **_Presentation layer (controllers)_**
* **_Application layer (services)_**
* **_Data access layer (DAO)_**


## Technologies
* Java 11
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