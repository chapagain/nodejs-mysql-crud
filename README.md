Node.js, Express & MySQL: Simple Add, Edit, Delete, View (CRUD)
========

A simple and basic CRUD application (Create, Read, Update, Delete) using Node.js, Express, MySQL & EJS Templating Engine.

**Blog:** [Node.js, Express & MySQL: Simple Add, Edit, Delete, View (CRUD)](http://blog.chapagain.com.np/node-js-express-mysql-simple-add-edit-delete-view-crud/)

**Creating database and table**

```
create database test;

use test;

CREATE TABLE users (
id int(11) NOT NULL auto_increment,
name varchar(100) NOT NULL,
age int(3) NOT NULL,
email varchar(100) NOT NULL,
PRIMARY KEY (id)
);
```
