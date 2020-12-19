# Burger

This project was designed as a homework assignment for MSU's coding bootcamp. 

This project has been loaded to my Personal GitHub Page and deployed to my Heroku account. To get this project up and running, you can follow the deployment link that I have included in the Link Section below.

# Table of Contents
1. [Links](#Links)
2. [Project Overview](#projectoverview)
3. [Demo](#demo)
4. [Assignment](#assignment)
5. [File Structure](#filestructure)
6. [License](#license)
7. [Execution](Execution)
8. [Contains](#contains)
9. [Credit](#credit)
10. [Creators](#creators)

## Links

* [GitHub Repository](https://github.com/JC72/Burger)
* [Active Site](https://stormy-lowlands-00833.herokuapp.com/)

## Project Overview <a name="projectoverview"></a>
* Uses CSS, Node.js, JQuery, JSON, AJAX, Express, express-handlebars and Heroku to create a active web page which allows the user to write burger names, save them, move them and delete them from the site.  This is accomplished using CRUD (create, retrieve, update & delete) and MVC (Model-view-controller).

## Demo:

![](https://github.com/JC72/Burger/blob/main/public/videos/demovideo.gif)

## Assignment
### This assignment contains the following features:

* Main Page
    * Contains a header with a image and name for the application.
    
    * A input section to enter the type of burgers you would like to add to wish list

    * A Burger wish list container where the burgers you would like to eat are stored after entering them.  It also has two buttons named "Enjoy!" & "Trash".

    * A Burger Ate container where burgers are moved to when the "Enjoy!" button is pressed.  This also contains two buttons name "Wish Again" & Trash".  The "Wish Again" button moves the Burger back into the Burger wish container.

    * The "Trash" button removes the Burger name from the site and the database.

    ![Home Page](https://github.com/JC72/Burger/blob/main/public/screenshots/mainpage.png)

    ![Entered Page](https://github.com/JC72/Burger/blob/main/public/screenshots/enterpage.png)

    ![Ate Page](https://github.com/JC72/Burger/blob/main/public/screenshots/atepage.png)



## File Structure <a name="filestructure"></a>

The following folders and what they contain are listed below:

```bash
  |-- BURGER
    |-- config
    |   |-- connection.js
    |   |-- orm.js
    |-- controllers
    |   |-- controller.js
    |-- db
    |   |-- schema.sql
    |   |-- seed.sql
    |-- models
    |   |--burger.js
    |-- public
    |   |-- assets
    |   |   |-- css
    |   |   |   |-- burger_style.css
    |   |   |-- img
    |   |   |   |-- burger.png
    |   |   |   |-- burger2.png
    |   |   |-- js
    |   |   |   |-- burger.js
    |   |   |-- screenshots
    |   |   |   |-- mainpage.png
    |   |   |   |-- enterpage.png
    |   |   |   |-- atepage.png
    |   |   |-- Videos
    |   |   |   | - demovideo.gif
    |-- views
    |   |-- layouts
    |   |   |-- main.handlebars
    |   |-- partials/burgers
    |   |   |-- burger-block.handlebars
    |   |   |-- burger-delete.handlebars
    |   |-- index.handlebars
    |-- .gitignore
    |-- LICENSE
    |-- README.md
    |-- package-lock.json
    |-- package.json
    |-- server.js
```

## License

This project is licensed under the MIT License License

![Badge for GitHub repo license](https://img.shields.io/github/license/JC72/Burger?style=flat&logo=appveyor)

## Execution
### To Execute File:
> Just click on the Active site link in the link section or go to
https://stormy-lowlands-00833.herokuapp.com/ in the web browser.

### Contains:

* Two Sql files
    * schema.sql
    * seeds.sql

* One css file
    * burger_styles.css

* Six javascript files
    * connection.js 
    * orm.js
    * controller.js
    * burger.js
    * burgers.js
    * server.js

* Four Handlebars Files
    * main.handlebars
    * burger-block.handlebars
    * burger_delete.handlebars
    * index.handlebars
        
* Package.json
    * Contains:
        * express
        * express-handlebars
        * mysql


## Credit

* Would like to thank stackoverflow for helping me find fixes for some of my conflicts.  Especially with my problem when trying to fix my deployment issue with Heroku and connecting the database.

* [Stack Overflow](https://stackoverflow.com/)

## Creators:

* **Jeff Clegg** - [Git Hub Profile](https://github.com/JC72)
* MSU BootCamp