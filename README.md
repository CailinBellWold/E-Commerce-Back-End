# 13 Object-Relational Mapping (ORM): E-Commerce Back End

[![License: MIT](https://img.shields.io/github/license/CailinBellWold/Team-Profile-Generator?style=plastic)](https://opensource.org/licenses/MIT)

## Description 
Refactor starter-code to build the back-end for an e-commerce site, including configuring a working Express.js API using Sequelize to interact with a MySQL database. 

### Motivation
Understanding the fundamental architecture of e-commerce platforms. 

### Learning Targets
This exercise provided opportunities to test my budding skills with Express.js configuration and using Sequelize. 

## Table of Contents
- [Core Objectives Met](#Core)
- [Technologies Used](#Technologies)
- [Local Installation & Usage](#Local)
- [Deployed App](#Deployed)
- [Demo](#Demo)
- [License](#MIT)
- [Questions](#Questions)

## Core Objectives Met

1. When a user adds a database name, MySQL username, and MySQL password to an environment variable file, they are able to connect to a database using Sequelize. 
2. When a user enters schema and seed commands, a development database is created and is seeded with test data.
3. When a user enters the command to invoke the application, their server is started and the Sequelize models are synced to the MySQL database.
4. When a user opens API GET routes in Insomnia Core for categories, products, or tags,the data for each of these routes is displayed in a formatted JSON.
5. When a user tests API POST, PUT, and DELETE routes in Insomnia Core, they are able to successfully create, update, and delete data in their database.

## Technologies Used
- JavaScript
- Node.js
- [NPM Express.js Package](https://www.npmjs.com/package/express)
- [NPM MySQL2 Package](https://www.npmjs.com/package/mysql2)
- [NPM Sequelize Package](https://www.npmjs.com/package/sequelize)
- [NPM DotENV Package](https://www.npmjs.com/package/dotenv)
- [NPM Router Package](https://www.npmjs.com/package/router)
- [NPM Nodemon Package](https://www.npmjs.com/package/nodemon)

## Local Installation & Usage

To use this app, you will need a MySQL Workbench account, and to have the app installed on your machine. Documentation with installation instructions are available [here.](https://dev.mysql.com/doc/workbench/en/wb-installing.html) 

To test the API routes in this app, you may wish to have an Insomnia account and to have the app installed on your machine. Documentation and instructions are available [here.](https://support.insomnia.rest/article/156-installation1) 

STEP 1

    1.1 Clone this E-Commerce-Back-End repo to your machine.

STEP 2

From Visual Studio Code or the code editor of your choice:

    2.1 Open the repo.  
    2.2 Locate and open the .env.EXAMPLE file, located in the root directory.
    2.3 Add your own MySQL Workbench Username and Password to the env.EXAMPLE file.
    2.4 Re-name the file to .env (i.e. remove .EXAMPLE).
    2.5 Save your changes.
    2.6 Locate and open db\schema.sql.
    2.7 Copy and paste the database schema into a new MySQL Workbench query tab and run it. Refresh and view your updated schemas to ensure that ecommerce_db now appears.

STEP 3

From your terminal, run:

    3.1 npm i
    3.2 npm run watch

STEP 4: API ROUTE TESTS

From your terminal, run:

    4.1 npm run seed

From Insomnia:

    4.2 Run tests for each API route (GET all, GET by id, PUSH, PUT, and DELETE) route using http://localhost:3001/api/ for each model (Category, Product, and Tag), with pathing listed as categories, products, and tags (i.e. GET http://localhost:3001/api/categories/).

## Demo 

Link: [E-Commerce Back End demo](https://drive.google.com/file/d/11zqLEt2JPkhQ4oXEBSG3pniiwvqssNfQ/view)

## MIT License
&copy;2021 Cailin Bell Wold

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Questions
For inquiries, please contact [Cailin Bell Wold](https://github.com/CailinBellWold).