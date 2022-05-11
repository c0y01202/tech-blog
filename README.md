# tech-blog

## Purpose of Project

The purpose of this project was to build a CMS-style blog site where developers can push their blog posts and comment on other developers' posts. This application was structured using the MVC paradigm, using Handlebars.js as the templating course to dynamically generate HTML pages, Sequelize as the ORM and the express-session npm package for user-authentication.

The project files and folders are sructured using the Model-View-Controller paradigm. After requiring certain node packages, routes were established in the Controllers folder. Then database schema and seeds were sourced into the project using Sequelize. HTML and CSS were added to the Views folder in Handlebars.js format. A login page with code for user authentication was added and also tested. A node package known as bcrypt was added to perform the hashing function for user passwords. Once the database connected to the server, it was tested with Insomnia. The ability to post information, log out and log in was tested. The project was then launched to Heroku as a live interactive tech-blog site.

## Resources

1. Visual Studio
2. Express Handlebars.js
3. Sequelize
4. Express
5. Express-session
6. Jest
7. Mysql2
8. Insomnia

## Link to Live Site:

https://mighty-escarpment-27826.herokuapp.com/

## Link to GitHub Repository:

https://github.com/c0y01202/tech-blog
