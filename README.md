#Taxi Service Project
This is a web app that has several options in web-browser 
to work with Database of drivers, cars and manufacturers
With this app you can:
1. Without registration:
* Watch registration page
* Watch add/drivers page
2. With registration:
* Register new drivers
* Add drivers to cars
* Add new cars and their manufacturers
* Delete cars, drivers and manufacturers
* Track all available cars and working drivers
* Track your cars as a driver
### Structure for future deployment
Project base on 3-layered architecture:
1. Data access layer (DAO)
2. Application layer (service)
3. Presentation layer (controllers)
### List of Technologies:
You can find needed dependencies in pom.xml file
* JDK 11
* Apache Tomcat (v9.0.55)
* Log4j (v2.14.1)
* MySQL (v8.0.22)
* JDBC
* Javax Servlet (v4.0.1)
* JSTL (v1.2)
* JSP
* Maven
* Maven Checkstyle Plugin
* HTML, CSS

### Recommendation for setup
1. Configure Apache Tomcat for your IDE
2. Install MySQL and MySQL Workbench or use terminal
3. Register new user in MySQL Connections
4. Cope and paste SQL schema from resources/init_db.sql in MySQL Workbench or terminal
5. In the /util/ConnectionUtil.java fill the URL, USERNAME and PASSWORD with your user properties that you have created earlier
6. Also, In the log4j2.xml change fileName path with the absolute path to file if you wish
7. You are ready to use the app