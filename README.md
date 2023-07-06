# E-commerce

## Description

This project can be used as a tool for user to store information about their business's inventory in a local database. The user can display, add, and delete items from the datatables that they will create by following the installation instructions.

## Installation

To install this project you must first clone the repository. The user must then start up their local MySQLserver connection and confirm in config folder that the connection.js file contains the correct port connection code, username, and password for their database to connect properly. After doing so the user can go in to the db folder and copy lines 1-3 in the schema.sql to be pasted into their personal sql database. Doing so will create the ecommerce_db. In order for the application to work properly the user must open up the main 'E-commerce' file in the intergrated terminal and enter 'npm i'. Doing so will install all the necessary packages needed for the application to run. While still in the terminal the user can now enter 'node seeds/index.js' to insert into the data tables with the information that is included in the seeds folder. Once the database is seeded the user can now enter 'npm start' into the terminal for the application to start running. Once the user is notified what port the application is listening for the user can open the insomnia application to view, add, or delete information using the http endpoints corresponding to the data they want to manipulate or view.

## Usage

Once the installation proccess has been completed and the user has entered 'npm start' while in the intergrated terminal for the 'E-commerce' file, the user can now manipulate and display all the tables included in the ecommerce_db through the corresponding endpoints in insomnia. While in insomnia the user can use the GET routes to access all the data from the three routes available or they can access individual items by specifying their id in the https endpoint. Along with the ability to use the GET routes the user is also capable of using the POST, PUT, and DELETE routes to add or remove data from their desired data table.

## GitHub Link

https://github.com/Anthony-D99/E-commerce