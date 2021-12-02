# Tech_Blog

## Description
This is a CMS style blog site for users to view and share posts about technology. Users are able to view posts from other users, as well as create, edit, delete their own posts. This application follows the MVC paradigm in the architectural structure with the use of many npm dependencies

## Table of Contents

* [Installation and setup](#install)
*
*
*


## Installation and Setup<a id = "install"></a>

First clone the files into the desired directory using the command line. Then run the command `npm install`. This will install all the required dependencies and packages for the application. Then make sure you have your mysql server setup for working on this application on your local computer, then enter your sql server with the command `mysql -u root -r` then your sql password. Then run the code `source db/schema.sql` to select the correct database. Then seed the database with the command `node seeds`. Now the database has been created and seeded. Then for security create a `.env` file and input the database name and your mysql username, and password in this format - 

* DB_NAME='tech_blog'
* DB_USER='*your MySql username here*'
* DB_PW='*your MySql password here*'

Now run the command npm start to start the application and type `http://localhost:3001/` and youll be directed to the application with all the seeded information.

## Usage

When the user first opens the site they are greeted with a dashboard of multiple posts, the suer that created it and the date they created it. As well as the login button. If the users decides to login or signup they can then comment and like posts as well as create their own posts

## License

[MIT](./LICENSE.txt)

## Credits

* [UCF Coding Bootcamp](https://github.com/coding-boot-camp/)

## Dependencies and Technology

## Authors

## Contact

## Road Map