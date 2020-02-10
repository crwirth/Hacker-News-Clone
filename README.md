# Hacker News Clone

In this project, I created a clone of the popular news-aggregator site Hacker News. It allows users to create accounts, log in, create articles, mark articles as favorites, and more.

This project focused on how to use an existing API to build out the functionality in front-end Javascript using jQuery and AJAX.

## There are two JavaScript files:
- api-classes.js
  - This file contains the classes I used and stored all the logic for communicating with the API.
- ui.js
   - This file makes use of the classes in api-classes.js and contains all of the DOM manipulation and jQuery code necessary.

## Functionality 
When a user has successfully logged in, a secured string or “token” is sent back from the server. 

Note also that when the page refreshes, the user can stay logged in. This is because I am storing the token in localStorage.

### Creating New Stories

Once a user has logged in, the application allows them to create a new story. This involved adding a new form that when submitted will send the data in the form to the API, which will respond with the newly created story. The newly created story is then appended to the DOM.

The method for creating a story is defined in the StoryList class of the api-classes.js file.

As a note - there is a task on the backend that will delete stories every day.

### Favoriting stories

Logged in users can “favorite” and “un-favorite” a story. These stories remain favorited when the page refreshes.

Logged in users can see a separate list of favorited stories.

The methods for favoriting and unfavoriting a story should be defined in the User class in the api-classes.js file.

### Removing Stories

Logged in users can remove a story. Once a story has been deleted, it is removed from the DOM and when the page refreshes, the story is deleted.







