# angular-mysql-php

## Description

A starter project for using AngularJS with Jade and Gulp to manipulate MySQL databases.

## Installation

1a. To install front-end dependencies, run the following command:

```Shell
path/to/your/installation$ bower install
```

1b. To install back-end dependencies (mainly for Gulp), run the following command:

```Shell
path/to/your/installation$ sudo npm install
```

2. Then create a MySQL database using the platform of your choice (e.g., by going to phpMyAdmin on your local or remote server) named "classicmodels."

3. After that, import _classicmodels.sql_ (located in the root directory of the project) into your new "classicmodels" database.

4. Finally, be sure to edit accordingly the relevant database constants in _api.php_ (located in the services directory). It looks like this by default:

```PHP
const DB_SERVER = "localhost";
const DB_USER = "root";
const DB_PASSWORD = "";
const DB = "classicmodels";
```

That should work for many local installations.