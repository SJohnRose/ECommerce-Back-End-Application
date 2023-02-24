# ECommerce-Back-End-Application
Back end for an e-commerce site using Express.js API and Sequelize package to interact with a MySQL database.

# Features
The Ecommerce Back End application has the following features:
* Back end for an ecommerce website using latest technologies.
* Express.js API on top of node.js has been used to build the application.
* Sequelize package is used to interact with MySQL database.
* Mysql2 package is used for creating database.
* dotenv package is used to manage environment variables.

# User Story
AS A manager at an internet retail company  
I WANT a back end for my e-commerce website that uses the latest technologies  
SO THAT my company can compete with other e-commerce companies  

# Acceptance Criteria
GIVEN a functional Express.js API  
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
THEN I am able to connect to a database using Sequelize  
WHEN I enter schema and seed commands  
THEN a development database is created and is seeded with test data  
WHEN I enter the command to invoke the application  
THEN my server is started and the Sequelize models are synced to the MySQL database  
WHEN I open API GET routes in Insomnia Core for categories, products, or tags  
THEN the data for each of these routes is displayed in a formatted JSON  
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core  
THEN I am able to successfully create, update, and delete data in my database  

# Installation
Please use 'npm install' to install the express, sequelize and dotenv packages
Please create a .env file in root folder with database name, user name and password.

# Usage
* the tables need to be seeded using the command 'npm run seed'
* the server needs to be started using the command 'node server.js'
* the routes can be tested using the insomnia app.

# How to access the application?
Please use this link: https://github.com/SJohnRose/ECommerce-Back-End-Application 

# Walkthrough video:
