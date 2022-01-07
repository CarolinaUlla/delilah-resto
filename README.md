# delilah-resto 🍕🍜🍰

API for placing and managing orders.


Resources and technologies used:
- Node Js
- Express
- Body-parser
- Sequelize
- JWT
- Bcrypt
- Moment

Necessary resources:
- Node
- MySQL

Steps to use the API:
1) clone the repository:
git clone https://github.com/CarolinaUlla/delilah-resto
2) in the console, npm install
3) In the MySql database engine, copy the queries found in the scripts.txt file and execute them so that the database is created.
In it, the administrator user (user: Caro08, password: contra) already has administrator permissions to access the different endpoints.
There are also some products inserted (3) to be able to use them to test the order endpoints.
4) In line number 6 of the app.js file (const sequelize = new Sequelize ('mysql: // root: tupassword @ localhost: 3306 / delilah'), you need to replace "tupassword" with the password you use to access to your database.
5) From postman open the file delilah.postman_collection.json where all the endpoints are located to test the API
6) All the corresponding documentation can be found at: https://app.swaggerhub.com/apis-docs/CarolinaUlla4/Delilah-Resto/1.0

HAPPY HACKING !
