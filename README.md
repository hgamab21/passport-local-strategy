# Passport: Local Strategy

A basic example of using passport.js with sequelize and express to create a simple login with authentication using a Local Strategy.

### Background

As a TA for a web development course, students of mine wanted an example of a basic passport use-case. The problem I ran into, however, was that many of the examples that I saw were outdated and required updating - not very student-friendly. So i went about taking one of the examples and updating it for them to study and implement themselves.

### Features

* Input validation
* Local Strategy authentication

### Technologies

* Node
* MySQL (via Sequelize)
* Express
* Passport.js (http://www.passportjs.org/)

## Installation

This app uses a MySQL database, you can download it here: (https://www.mysql.com/downloads/)

Use the Node Package Manager [npm](https://www.npmjs.com/) first to install all necessary dependencies.

```bash
npm i
```

NOTE: This also uses the module 'mysql2' as a dependency, you will need to install this as well after your inital install:

```bash
npm i mysql2
```
Finally, for proper usage please make sure your MySQL credentials are included. To do this, put your credentials in app/config/config.json where indicated:

```json
"development": {

        "username": "root" OR "your_username",

        "password": null OR "your_database_password",

        "database": "sequelize_passport",

        "host": "127.0.0.1",

        "dialect": "mysql"

    },
```