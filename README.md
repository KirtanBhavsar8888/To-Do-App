# To-Do App for Dendrite.ai#
This Project is Done by Kirtan Bhavsar.
To-Do application based on Python/Flask Backend JWT and a Javascript/React/Redux Front-End with Material UI.

- Python 3.x
- Pytest
- Flask
- React
- Redux
- React-Router 2.0
- React-Router-Redux
- Babel 6
- SCSS processing
- Webpack

### Introduction

A modern Web Application is made up of three main components:

- Front-end;
- Back-end;
- Database;

### Description

To make the project well structured we will keep those components separated. A popular and productive technology stack today is a combination of React/Redux for the front-end, Python/Flask for the backend, and SQLAlchemy as the Python Object Relation Map (ORM) to communicate with your SQL database.

This project showcases a fully functional To-Do application, allowing users to manage their tasks efficiently. The application uses JWT (JSON Web Tokens) for secure authentication and authorization. The React front-end provides a smooth and interactive user experience, while the Flask back-end ensures robust data handling and API endpoints.

### Install Back-End Requirements

```sh
$ pip install -r requirements.txt
```

### Install Front-End Requirements

```sh
$ cd static
$ npm install
```

### Install Database

- Install the free community edition of [MySQL](https://dev.mysql.com/downloads/mysql/) and [MySQL Workbench](https://www.mysql.com/products/workbench/)
- Create Scheme "mydatabase"
- Add configuration string to file config.py: `mysql+mysqlconnector://root:admin@localhost/mydatabase`
- Create tables `python manage.py create_db`

### Run Back-End

```sh
$ python manage.py runserver
```

### Run Front-End

```sh
$ cd static
$ npm start
```

### Run

Open your browser to `http://localhost:3000`

Enjoy! If you have any questions, please feel free to send me a message!
