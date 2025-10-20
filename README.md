# Phonebook-Application
# Phonebook Application(Web-App)☎️📶📞

## My Goal

The objective of this project was to build a web application known as Phonebook application, which is developed using Java MVC, Servlets and JSP. The application contains register/login validations. It uses an online local database known as h2 Database engine for authenticating its users and storing the data for each user respectively. As the name of the app suggests, a user can maintain his/her own contact list. The end-user can add new contact details, view all saved contacts, edit already saved contacts as well as delete saved contacts. Also the application contains different kinds of themes which the end-user can change dynamically using separate buttons, hence providing a beautiful user interface.


# Introduction
Creating a Phonebook application using JSP, Java, and MySQL is a great project to enhance your skills in web development and database management. This web application allows users to store, manage, and search contact information efficiently. In this blog post, we will guide you through the steps to create a phonebook application from scratch, highlighting essential features, required software and tools, and providing screenshots and download links for the project.

# Step 1: Making the Project

To start, you need to set up a new project in your Integrated Development Environment (IDE) such as Eclipse or IntelliJ IDEA.


# Project Structure

Create a Dynamic Web Project in your IDE.
Configure the project to use Apache Tomcat server.
Set up the folder structure as follows:

src for Java source files
WebContent for JSP files and static content (HTML, CSS, JavaScript)
WEB-INF for web.xml and lib folder for dependencies

# Database Setup

Create a MySQL database named phonebook_db.
Create a table named contacts with the following schema:

# Java and JSP Setup

1.Create Java Beans for Contact:

2.Create Data Access Object (DAO) for database operations:

3.Create JSP files for user interface:

index.jsp for home page
addContact.jsp for adding new contacts
viewContacts.jsp for displaying contacts

# Step 2: Essential Features

Your phonebook application should have the following essential features:


# Add Contact

Allow users to add new contacts with name, phone number, and email address.


# View Contacts

Display a list of all contacts stored in the database.


# Update Contact

Enable users to update existing contact information.


# Delete Contact

Allow users to delete contacts from the database.


# Search Contact

Provide a search functionality to find contacts by name, phone number, or email.


# Step 3: Required Software and Tools

To build and run this project, you will need the following software and tools:


Java Development Kit (JDK) 8 or higher
Eclipse IDE or IntelliJ IDEA
Apache Tomcat 8 or higher
MySQL Database
MySQL Connector/J (JDBC driver)

# Step 4: Running the Project

Follow these steps to run the project:


Set up the database connection in your project by adding MySQL Connector/J to your project’s library.
Configure the database properties in a properties file or directly in your DAO class:

   String jdbcURL = "jdbc:mysql://localhost:3306/phonebook_db";
   String jdbcUsername = "root";
   String jdbcPassword = "password";

# Deploy the project to Apache Tomcat:

Right-click on your project > Run As > Run on Server > Select Tomcat Server

Access the application in your web browser at http://localhost:8080/PhonebookApp.

# Step 5: Project Screenshots

Here are some screenshots of the application to give you an idea of the interface and functionality:


Home Page


![MergedImages](https://user-images.githubusercontent.com/59922056/179366266-c7c410cd-b812-4b74-9ad9-80652ba04225.jpg)

![4](https://user-images.githubusercontent.com/59922056/179366358-3e63d53d-6c87-4ffb-9ff2-fd4cb8cf6c02.jpg)

Add Contact Page

![5](https://user-images.githubusercontent.com/59922056/179366365-48099e15-b2be-4096-90a5-5a1f927a406c.jpg)


View Contacts Page

![6](https://user-images.githubusercontent.com/59922056/179366385-7f1bb7a0-fb1c-4fcd-8711-55d5f4b44f09.jpg)



Tags

Phonebook Application
Web Application
JSP
Java
MySQL
CRUD Operations
Database Management



