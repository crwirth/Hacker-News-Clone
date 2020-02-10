# Hacker News Clone

In this project, I created a clone of the popular news-aggregator site Hacker News. It allows users to create accounts, log in, create articles, mark articles as favorites, and more.

This project focused on how to use an existing API to build out the functionality in front-end Javascript using jQuery and AJAX.

### There are two JavaScript files:
- api-classes.js
  - This file contains the classes I used and stored all the logic for communicating with the API.
- ui.js
   - This file makes use of the classes in api-classes.js and contains all of the DOM manipulation and jQuery code necessary.

### Functionality 
When a user has successfully logged in, a secured string or “token” is sent back from the server. 

Note also that when the page refreshes, the user can stay logged in. This is because I am storing the token in localStorage.





