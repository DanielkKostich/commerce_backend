# Commerce Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

https://app.screencastify.com/manage/videos/byQxPGz5GAIFchyNZ8CS

## Table of Contents

- [Installation](#installation)
- [API Routes](#api-routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

Follow these steps to install and set up the project locally:

1. Clone the repository.

 clone https://github.com/DanielkKostich/commerce_backend
 cd commerce_backend
Install the dependencies.

npm install


Create a .env file in the project's root directory.
Configure the database connection by adding the following lines to the .env file:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
Run database migrations and seed the database.

Start the application.

npm start



## API Routes
The project provides the following API routes:

Categories
GET /api/categories - Retrieve all categories.
GET /api/categories/:id - Retrieve a specific category.
POST /api/categories - Create a new category.
PUT /api/categories/:id - Update an existing category.
DELETE /api/categories/:id - Delete a category.
Products
GET /api/products - Retrieve all products.
GET /api/products/:id - Retrieve a specific product.
POST /api/products - Create a new product.
PUT /api/products/:id - Update an existing product.
DELETE /api/products/:id - Delete a product.
Tags
GET /api/tags - Retrieve all tags.
GET /api/tags/:id - Retrieve a specific tag.
POST /api/tags - Create a new tag.
PUT /api/tags/:id - Update an existing tag.
DELETE /api/tags/:id - Delete a tag.
For each route, specify the expected request/response formats and any additional details about the endpoint's functionality.


## Contributing
Thank you for considering contributing to the project! Follow the guidelines below to contribute:

Fork the repository.
Create a new branch for your feature/bug fix.
Commit your changes and push the branch to your fork.
Submit a pull request, describing your changes and their purpose.
Please ensure your code follows the project's coding style and includes appropriate tests.

## License
This project is licensed under the MIT License.