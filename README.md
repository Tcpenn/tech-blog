# Tech_Blog

## Description
This is a CMS style blog site for users to view and share posts about technology. Users are able to view posts from other users, as well as create, edit, delete their own posts. This application follows the MVC paradigm in the architectural structure with the use of many npm dependencies

## Table of Contents

* [Installation and setup](#install)
* [Usage](#usage)
* [License](#license)
* [Credits](#credits)
* [Dependencies and Technology](#tech)



## Installation and Setup<a id = "install"></a>

First clone the files into the desired directory using the command line. Then run the command `npm install`. This will install all the required dependencies and packages for the application. Then make sure you have your mysql server setup for working on this application on your local computer, then enter your sql server with the command `mysql -u root -r` then your sql password. Then run the code `source db/schema.sql` to select the correct database. Then seed the database with the command `node seeds`. Now the database has been created and seeded. Then for security create a `.env` file and input the database name and your mysql username, and password in this format - 

* DB_NAME='tech_blog'
* DB_USER='*your MySql username here*'
* DB_PW='*your MySql password here*'

Now run the command npm start to start the application and type `http://localhost:3001/` and you'll be directed to the application with all the seeded information.

You can also checkout the deployed application [here](https://floating-garden-75030.herokuapp.com/)

## Usage <a id = "usage"></a>

When the user first opens the site they are greeted with a dashboard of multiple posts, the suer that created it and the date they created it. As well as the login button. If the users decides to login or signup they can then comment and like posts as well as create their own posts

## License<a id = "license"></a>

[MIT](./LICENSE.txt)

## Credits<a id = "credits"></a>

* [UCF Coding Bootcamp](https://github.com/coding-boot-camp/)

## Dependencies and Technology<a id = "tech"></a>

Technologies
* [Node.js](https://nodejs.org/en/)
* [MySQL](https://www.mysql.com/)

Dependencies

* [Express](https://www.npmjs.com/package/express)
* [Sequelize](https://sequelize.org/)
* [Express-Session](https://www.npmjs.com/package/express-session)
* [Connect-session](https://www.npmjs.com/package/connect-session)
* [Connect-Session-Sequelize](https://www.npmjs.com/package/connect-session-sequelize)
* [Express-Handlebars](https://www.npmjs.com/package/express-handlebars)
* [Node MySQL 2](https://www.npmjs.com/package/mysql2?__cf_chl_captcha_tk__=pmd_D_9ZYQ1MY_s2zyp9_cyigjzi9F6rp.HQGrKz3R3K9gA-1632161698-0-gqNtZGzNAuWjcnBszQfR)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [Path](https://www.npmjs.com/package/path)
* [Bcrypt](https://www.npmjs.com/package/bcrypt)
* [Jest](https://www.npmjs.com/package/jest)

## Authors

Tyler Pennington

## Contact

[Github](https://github.com/Tcpenn)
[Email](mailto:tcpenn1026@gmail.com)

## Road Map

The plans for this app are to make a post content area for users to add descriptions for their posts and to spruce up the CSS.    