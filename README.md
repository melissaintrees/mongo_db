# NPR Music's The Record Webscraper

## About

Full Stack Webscraper with an Express server that uses Cheerio &Request to grab articles from NPR's the Record website section, and then stores them in a Mongodb database. The app gives you the option of saving and deleting articles from the database, and also gives you the option of writing notes related to the articles that you save. Data is dispersed using Handlebars and it was designed with the bootstrap 4 framework. It is deployed on [Heroku](https://npr-music-scraper.herokuapp.com/) and/or you can install it on your local machine.

## How it works

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Video
<<<<<<< HEAD
[![NPR Music's The Record Web Scraper](https://imgur.com/a/RCmxz)](https://vimeo.com/257386878 "Npr's The Record Web Scraper - Click to Watch!")
=======
 ![gif](https://media.giphy.com/media/fQlSG588m62TOg14EA/giphy.gif)

>>>>>>> 86b4c0e5e3990a30c31a3a375827aa8c7ee5253a

Though most of the logic is handled on the back end, Bootstrap was leveraged to provide a responsive and user friendly interface.

- All Screen Mock Up
  ![Mock Up](/screenshots/mockup_diff_screens.jpg)

- Full Screen View
  ![Full Screen](/screenshots/full_view.png)

- Mobile Screen View

  ![Mobile Screen](/screenshots/mobile_view.jpg)


## Deployment

To deploy in your system:

  1. Download the repo.
  2. In your terminal `npm install` to install the node dependencies
  3. In a new terminal tab, run `Mongo` and `Mongod`
  4. Run the server with Node JS by running `node server.js`

## Built With

* [NodeJs](https://nodejs.org/en/) - The programming framework
* [Express](https://expressjs.com/) - The server framework.
* [Request](https://cheerio.js.org/) - Jquery for the Server
* [Mongoose](http://mongoosejs.com/) - Database Management
* [Handlebars](http://handlebarsjs.com/) - Templating System
* [Bootstrap](http://getbootstrap.com) - Responsive Framework System

## Authors

* **Melissa St Moore** - *Initial work*

## Acknowledgments

* (https://github.com/tomtom28/mongodb-web-scraper) [Paper Scraper, code utilized]
* (https://github.com/luomichelle/Mongoose-and-Cheerio-) [Hologram News Cube]
