# NY Times MongoDB Scraper

## Overview

A web app that lets users view and leave comments on the latest news. The app uses Mongoose and Cheerio to scrape news from the New York Times website.


![alt text][logo]

[logo]: https://github.com/tellomp/mongodb-scraper/blob/master/public/assets/images/noArticles.png "no articles"


## Requirements and Instructions

* Whenever a user visits the site, the app scrapes stories from The New York Times and display them for the user.

* The app scrapes and displays the following information for each article:
  * Headline - the title of the article
  * Summary - a short summary of the article
  * URL - the url to the original article
  
  
![alt text][scraped]

[scraped]: https://github.com/tellomp/mongodb-scraper/blob/master/public/assets/images/scraped.png "Scraped"

* User is able to save a scraped article to the database and they can click on the article to read it full. 


![alt text][saved]

[saved]: https://github.com/tellomp/mongodb-scraper/blob/master/public/assets/images/savedArticle.png "Saved Article"


* Users are able leave comments on the articles displayed and revisit them later. 


![alt text][note]

[note]: https://github.com/tellomp/mongodb-scraper/blob/master/public/assets/images/note.png "Notes"


* The comments are saved to the database as well and associated with their articles. 
* Users are able to delete comments left on articles. 
* All stored comments are visible to every user.


![alt text][newNote]

[newNote]: https://github.com/tellomp/mongodb-scraper/blob/master/public/assets/images/savedNote.png "Saved Notes"


## Live App
* Scrape and add some articles to our database here! 

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
