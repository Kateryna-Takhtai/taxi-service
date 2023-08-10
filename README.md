# Taxi Service 🚕

Lovely web-application to enhance user experience about taxi service. 
The project implements driver authentication with different functionality. 
Once you login and create a new driver, you will be able:

* create/update/remove a car;
* create/update/remove a driver;
* create/update/remove a manufacturer;
* display list of all cars;
* display list of all drivers;
* display list of all manufacturers;


## Architecture 🏛
The project is based on a 3-layer architecture.
* Controllers(Presentation layer).
* Services(Application layer).
* DAO(Data access layer).


## Technologies 😎
* JDK(18)
* Maven(3.3.2)
* Apache Tomcat(10.1.11)
* MySQL(8.0.22)
* JDBC
* Servlet
* JSTL
* JSP
* HTML, CSS


## Set-up 🖥
* Clone the project from GitHub
* Use [/resources/init_db.sql]() to create a schema and tables
* Configure [/util/ConnectionUtil.java]() with your own URL, username, password and JDBC driver
* Configure Tomcat
* Run the program
