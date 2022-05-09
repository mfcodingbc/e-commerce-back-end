# E-commerce Back End

Create, update, access, and delete data from a development database

## Description

This back-end application allows one to connect to a database and seed said database with test data. After the database is set up, you can then access the data within and create, update, or delete the data in the database.

## Installation

Clone the code from the [GitHub repository](https://github.com/mfcodingbc/e-commerce-back-end)

## Usage

After cloning the code from the GitHub repository, install the necessary npm libraries with the command `'npm install'` Also, you will need to enter your `mysql` info in a `.env` file on the main directory as the following:  
`DB_NAME='database_name'`  
`DB_USER='your_username'`  
`DB_PW='your_password'`  
(The database name can be pulled from the `schema.sql` file found in the `db` folder)

Once this file has been created, you will then need to create the database by typing `'source db/schema.sql'` in the command-line (from the root directory of the application). After the database has been created, type `'npm run seed'` to seed the database with the test data. The console log will notify you that the database has been successfully seeded, after which you will type `'npm start'` to be able to access the database in Insomnia (or other app where you will make the api calls).

In Insomnia, you can make GET, POST, PUT, and DELETE requests to these routes:  
`'api/categories'`  
`'api/products'`  
`'api/tags'`

For further info on the requests that can be made, check out the following walkthrough video:

[E-commerce Back End App Walkthrough](link to video here)

## Technologies Used

- Express.js
- Node.js
- Heroku
- MySql
- Sequelize

## Credits

Created following the MSU Coding Bootcamp module on Express.js.  
Starting code made by [Xandromus](https://github.com/Xandromus).

## License

[MIT](https://choosealicense.com/licenses/mit/)
