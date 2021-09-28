# e-commerce backend

## Table of Contents

* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#question)

## Description

This is a backend app for an e-commerce site that the user to see, add, update and delete products. They also can do the same for Tag & Categories.

## Installation

Creat a new directory and execute the following command:
```
git@github.com:murda02/wk13-e-commerce-backend.git
```

After the repo is cloned you will need to install the dependencies, execute this command from the command-line in the root directory:
```
npm i
```

In order to use this app, you need MySQL installed on your local. 
1. Install MySQL. See installation guide [here](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/). 
2. Change the mysql database password in the `index.js` file to the root password you just setup in step 1.
3. Once MySQL is install, enter mysql from the root directory with this command: `mysql -u root -p`. 
4. Next create the database: `CREATE DATABASE ecommerce_db;` 
5. Select the database `use ecommerce_db;`

## Usage

Before starting the server and seeding the database, you will need to rename the `.env.EXAMPLE` to `.env` and enter your MySQL user & password and save.

See instructional video [here](https://drive.google.com/file/d/1jaed-lhJqnjGAGfRxZXttA_6rSWdDxtF/view?usp=sharing)

## License

MIT


## Questions
Contact me at:
* [GitHub](https://github.com/murda02)
* [Email](mailto:davelmurphy@zoho.com)