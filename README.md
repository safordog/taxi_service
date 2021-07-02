# TAXI SERVICE
This is an imitation of a taxi fleet management program.<br/>
The service allows registration and authentication drivers, logout, add a new car to the database, assign a car to a driver, also possible to delete this data and so on.<br/>
The project is provided with a simple graphical shell using **HTML** and **CSS**.<br/>
The program was built in accordance with the principles **SOLID** and **layered architecture**.

### Screenshots
#### *registration:*<br/>
![registration_page](screenshots/registration_page.png)
#### *login:*<br/>
![login_page](screenshots/login_page.png)
#### *main menu:*<br/>
![main_menu_page](screenshots/main_menu_page.png)
#### *all cars:*<br/>
![all_cars_page](screenshots/all_cars_page.png)
### The project used:
- Java WEB, Servlets, JDBC;
- HTML, CSS, JSP, JSTL;
- MySQL
- Tomcat;
- Maven;
- Log4j.

### To run the program:
- clone the project;
- configure the database connection file - *src/main/java/taxi/util/ConnectionUtil*:<br/>
  {<br/>
  - String URL = "jdbc:mysql://localhost:3306/**your database name**?serverTimezone=GMT";<br/>
  - String USERNAME = "**your database username**";<br/>
  - String PASSWORD = "**your database password**";<br/>
  - String JDBC_DRIVER = "com.mysql.cj.jdbc.Driver"; <br/>
    }<br/>
- configure Tomcat:<br/>
  {<br/>
  **IntellijIdea:**
  - Run –>> Edit Configurations…
  - Clicks **+** icon, select Tomcat Server –>> Local<br/>
  - Clicks on the **fix** icon and choose the exploded war version
  - On the **deployment** tab in **application context** field remove data and put **"/"**; 
  - Press **OK**.<br/>
  }<br/>

