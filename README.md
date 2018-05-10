# People Magazine Scrapper

### Overview

PeopleMagazine App allows the user to scrape recent articles with pictures. The user is able to save their preferred articles and add notes. 

You can check this app using heroku

https://fathomless-shore-48626.herokuapp.com/

### Dependencies

`express`: builds server-side routes and functions

`request`: enables `cheerio` to get access to front-end code of http://people.com/news/

`cheerio`: scrapes front-end code from http://people.com/news/

`mongoose`: is in charge of database 

`morgan`: logs server-side requests and helps with debugging

`express-handlebars`: handles multiple html pages