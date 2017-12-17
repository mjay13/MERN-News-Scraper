# MERN-News-Scraper

### Overview
This is a web app that lets users view and leave comments on the latest news utelizing the MERN stack.

- - -

### Deployment
This application is deployed to Heroku, view [here] (https://devcenter.heroku.com/articles/account-verification). 

- - -

### Functionality
Whenever a user visits the site, the app scrapes stories from a news outlet and displays them for the user. Each scraped article is saved to the application database, but with a check so that there are no duplicates. When the articles are scraped, the headline, a summary, and the url shown. Users are able to leave comments on the articles displayed and revisit them later as the comments are saved to the database as well and associated with their respective articles. Users are also able to delete those comments left on articles and all stored comments are visible to every user.

The React mounting life-cycle is used to query and display articles based on user searches as well as Node, Express, and MongoDB so that the users can save articles to read later.

This is a single page application that uses the `react-router-dom` to navigate, hide, and show the React components without changing the route within Express

- - - 

2017 Megan M. Jacobs