Taxi Service
====
This simple web application imitates a work of taxi service app with the ability to authenticate the driver as a user.

Project structure
-----------
Application is designed according to SOLID principles, using DAO, DI and N-Tier Architecture patterns with next layers:
1. controllers layer (the presentation tier);
2. services layer (the logic tier);
3. DAO layer (the data tier);

Features
-----------
1. Login / Logout
2. Create driver/ Delete driver
3. Display all drivers
4. Create manufacturer/ Delete manufacturer
5. Display all manufacturers
6. Create car/ Delete car
7. Display all cars
8. Add diver to car

Technologies
-----------
* Java 11
* JDBC
* JSP
* JSTL
* HTTP Filter
* Apache Tomcat(v9.0.50)
* Apache Maven
* MySQL

Usage
-----------
1. Install IntelliJ IDEA ultimate version;
2. Clone this project from GitHub and make sure that an absolute path doesn't include any white spaces and/or non-latin
   symbols;
3. Install and configure Apache Tomcat(v9.0.50), connect and configure Tomcat inside the application;
4. Install MySQL and MySQL Workbench;
5. Run script from the resources/init_db.sql file in the Workbench;
6. Using a Workbench add at least one driver to your DB;
7. Configure src/main/java/taxi/util/ConnectionUtil.java file to make a connection to you DB*;
8. Run application.

*  HINT: If you can't connect to your DB because of this error:
   The server time zone value ‘EEST’ is unrecognized or represents more than one time zone.
   Try to set timezone explicitly in your connection URL.
