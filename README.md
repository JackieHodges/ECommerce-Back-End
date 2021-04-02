# ECommerce-Back-End
ORM: ECommerce Back End


## Description

Using starter code, a back end for an e-commerce site was built for this project. Using an Express.js API and Sequelize, I was able to interact with a MySQL database.

The database name, MySQL Username, and MySQL password are all contained within an environmental variable file for sensitive data storage. Within the db file, the schema is written to be implemented in a MySQL workbench. Once the database is created, the seed command can be run to seed the data into the database.

The application is invoked using the command line/node. Once the connection is established, the user can use Insomnia core to open API GET, POST, PUT, and DELETE routes for categories, products, and tags. This was achieved by creating APU routes to perform RESTful CRUD operations. 

Associations were executed in the models to define the relationship between Products/Categories (Product belongs to one category, and a category can have many products) and Products/Tags (Product can have many tags, and tags can have many products).


## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)


## Installation

To install from GitHub, follow these steps:

* Pull the repository found here: [E-Commerce Back End Repo](https://github.com/JackieHodges/ECommerce-Back-End)
* Install dependencies by typing the following in the terminal: npm i
* Create the database by using the data in schema.sql in a program such as MySQL Workbench
* Seed the data by entering the following into your terminal: npm run seed
* Once the data has been seeded, run the application by entering: npm start


## Usage

Below is a gif of the application's functionality:

![video](Assets/ECommerce.gif)

[Click here](https://drive.google.com/file/d/1rd0QT0D8jzmznfnjAXZRD7ycpAec5UEH/view) to view it in a larger version.


## Credits

[MySQL2](https://www.npmjs.com/package/mysql), [Sequelize](https://www.npmjs.com/package/sequelize), and [dotenv](https://www.npmjs.com/package/dotenv) were used in this application.