# All the News That's Fit to Scrape

### Overview

This is a web app that lets users view and leave comments on the latest news. But instead of writing any articles; instead, I used Mongoose and Cheerio to scrape news from another site.

### Dependencies

express

express-handlebars

mongoose

body-parser

cheerio

request



10. We used mLab to deploy the project to heroku. mLab is remote MongoDB database that Heroku supports natively. 

## Instructions

* Create an app that accomplishes the following:

  1. Whenever a user visits your site, the app should scrape stories from a news outlet of your choice and display them for the user. Each scraped article should be saved to your application database. At a minimum, the app should scrape and display the following information for each article:

     * Headline - the title of the article

     * Summary - a short summary of the article

     * URL - the url to the original article


  2. Users should also be able to leave comments on the articles displayed and revisit them later. The comments should be saved to the database as well and associated with their articles. Users should also be able to delete comments left on articles. All stored comments should be visible to every user.


### Helpful Links

* [MongoDB Documentation](https://docs.mongodb.com/manual/)
* [Mongoose Documentation](http://mongoosejs.com/docs/api.html)
* [Cheerio Documentation](https://github.com/cheeriojs/cheerio)

- - -
