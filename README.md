# NY Times MongoDB Scraper

## Overview

A web app that lets users view and leave comments on the latest news. The app uses Mongoose and Cheerio to scrape news from the New York Times website.

## Requirements and Instructions

* Whenever a user visits the site, the app scrapes stories from The New York Times and display them for the user. Each scraped article is saved to the database. 

* The app scrapes and displays the following information for each article:
  * Headline - the title of the article
  * Summary - a short summary of the article
  * URL - the url to the original article

* Users are able leave comments on the articles displayed and revisit them later. 
* The comments are saved to the database as well and associated with their articles. 
* Users are able to delete comments left on articles. 
* All stored comments are visible to every user.

## Technologies Used
* Express.js
* Express-handlebars
* Mongoose
* Cheerio
* Axios
* MongoDB
* Node.js
* JavaScript
* Heroku
* mLab
