# Login-Project-Using-Python-Flask-and-MySQL

Project Title: Login and registration Project using Flask framework and MySQL Workbench.

Type of Application (Category): Web application.

Introduction: A framework is a code library that makes a developer’s life easier when building web applications by providing reusable code for common operations. There are a number of frameworks for Python, including Flask, Tornado, Pyramid, and Django. Flask is a lightweight web application framework. It is classified as a micro-framework because it does not require particular tools or libraries. 

Pre-requisite: Knowledge of Python, MySQL Workbench and basics of Flask Framework. Python and MySQL Workbench should be installed in the system. Visual studio code or Spyder or any code editor to work on the application. Technologies used in the project: Flask framework, MySQL Workbench. 

Implementation of the Project: 

(1) Creating Environment 

Step-1: Create an environment. Create a project folder and a venv folder within. 
py -3 -m venv venv
Step-2: Activate the environment.
venv\Scripts\activate
Step-3: Install Flask.
pip install Flask

(2) MySQL Workbench 

Step-1: Install MySQL workbench. Link to install : https://dev.mysql.com/downloads/workbench/ Know more about it : https://www.mysql.com/products/workbench/ 
Step-2: Install ‘mysqlbd’ module in your venv.
pip install flask-mysqldb

Step-3: Open MySQL workbench. 
Step-4: Write the following code. The above SQL statement will create our database geeklogin with the table accounts. 
Step-5: Execute the query.

(3) Creating Project 

Step-1: Create an empty folder ‘login’. 
Step-2: Now open your code editor and open this ‘login’ folder. 
Step-3: Create ‘app.py’ folder .
Step-4: Create the folder ‘templates’. create the file ‘login.html’, ‘register.html’, ‘index.html’ inside the ‘templates’ folder. 
Step-5: Open ‘login.html’ file and write the code given below. In ‘login.html’, we have two fields i.e. username and password. When user enters correct username and password, it will route you to index page otherwise ‘Incorrect username/password’ is displayed. 
Step-6: Open ‘register.html’ file and write the code given below. In ‘register.html’, we have three fields i.e. username, password and email. When user enters all the information, it stored the data in the database and ‘Registration successful’ is displayed. 
Step-7: Open ‘index.html’ file and write the code given below. This page is displayed when login is successful and username is also displayed. The logout functionality is also included in this page. When user logs out, it moves to fresh login page again. 
Step-8: Create the folder ‘static’. create the file ‘style.css’ inside the ‘static’ folder and paste the given CSS code. 

Step-9: The project structure will look like this.   ![structure4](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/9f7aa1f3-602a-4dbe-9782-a35bb2bb518f)

(4) Run the Project 

Step-1: Run the server. 
Step-2: Browse the URL ‘localhost:5000’. 
Step-3: The output web page will be displayed. 

(5) Testing of the Application 

Step-1: If you are new user, go to sign up page and fill the details. 
Step-2: After registration, go to login page. Enter your username and password and sign in. 

Step-3: If your login is successful, you will be moved to index page and your name will be displayed. Output: Login page:  ![login2](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/ab59de7a-312c-487a-9c80-a6ab18a9ab3b)

Registration page:  ![register](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/d781062b-e649-4b9c-b46e-b5b389a0fa29)

If registration successful:  ![register_scuccess](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/e53ada4e-c18e-49ba-8051-ae65f96bcd25)

Before registration, Database table: ![beforereg](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/22be5965-d83b-4484-9ac1-127874385952)


After registration, Database table:  ![afterreg](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/a69ed502-295f-4783-a400-4bfb4d0ae05f)

If login successful, Indexpage is displayed:  ![index6](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/8e5eb8ac-5f05-4a20-9a54-814380e2edba)


If Login fails:   ![login_fail](https://github.com/MayankTomar21/Login-Project-Using-Python-Flask-and-MySQL/assets/81947542/732262b3-cce9-40be-acb4-e6a2ef854c26)
