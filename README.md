# Ecommerce-backend

![license](https://img.shields.io/badge/License-The_unlicense-blue)

# Description

This application runs the back-end for an e-commerce store. You can manage your store's categories, products, as well as a number of tags to associate with each product.

# Table of Contents
- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [Credits and Questions](#Credits)
- [License](#License)

# Installation
[Instructional Video!](https://)

To use this application you must have Node.js and SQL installed on your system. Visit [node installation](https://nodejs.org/en/download/) and [SQL installation](https://dev.mysql.com/downloads/mysql/) to download and install.

After installing the required softwares, clone the repository. In the terminal, navigate to the application's directory, then run the following command once:
```
npm install
```

After that, log into the MySQL shell, initialize the database, then exit the shell.
```
mysql -u root -p
source db/schema.sql
exit
```
Seed the database with some starting data.
```
npm run seed
```

# Usage
Once you have set up the app following the instructions above, you can run it by entering the following:
```
npm start
```
The application will execute in your terminal. You can test routes by navigating to the appropriate URLs in your browser, or using the Insomnia app.


# Questions 

Contact information is provided below:
* Author: Yashar Sarabi
* Github: [Yasharjs](https://github.com/yasharjs)
* Email: yasharjs@gmail.com

# License
This project is licensed under the [The Unlicensed](https://choosealicense.com/licenses/unlicense/)
