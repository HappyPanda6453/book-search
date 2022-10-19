
> Link web page: https://dg-book-search-engine.herokuapp.com/


## Description

GIVEN a book search engine

- Loading the search engine, I will presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.

- Clicking on the Search for Books menu option, I will presented with an input field to search for books and a submit button.

- If I am not logged in and enter a search term in the input field and click the submit button, I will be presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site.

- Clicking on the Login/Signup menu option,a modal will appear on the screen with a toggle between the option to log in or sign up.

- If the toggle is set to Signup, I am presented with three inputs for a username, an email address, and a password, and a signup button.

- If the toggle is set to Login, I am presented with two inputs for an email address and a password and login button.

- Entering a valid email address and create a password and click on the signup button, my user account will be created and I am logged in to the site.

- Entering my account’s email address and password and click on the login button, the modal closes and I am logged in to the site.

- If I am logged in to the site, the menu options change to Search for Books, an option to see my saved books, and Logout.

- Being logged in and enter a search term in the input field and click the submit button, I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account.

- Clicking on the Save button on a book, that book’s information is saved to my account.

- Clicking on the option to see my saved books, I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account.

- Clicking on the Remove button on a book, that book will be deleted from my saved books list.

- Clicking on the Logout button, I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.


- <p><a href="https://www.mongodb.com/">MongoDB</a></p>
- <p><a href="https://www.heroku.com/">Heroku</a></p>

[Back To Top](#book-search-engine)

---

## How to Download

- Simply copy the **SSH** to the terminal or Download the **ZIP File**:

## Installation


  git status

  git add -A

  git commit -m "Message to commit."

  git push or git push origin main
  ```

## Prerequisites

Before of using this application, is require to install dependencies, run the following command in your terminal:

```
npm install
```

[Back To Top](#book-search-engine)

---

## Usage

This is a open source program, feel free to use it, contact me to request features.

```javascript
 "scripts": {
    "start": "if-env NODE_ENV=production && npm run start:prod || npm run start:dev",
    "start:prod": "cd server && npm start",
    "start:dev": "concurrently \"cd server && npm run watch\" \"cd client && npm start\"",
    "install": "cd server && npm i && cd ../client && npm i",
    "heroku-postbuild": "cd client && npm run build"
  }
```

### `npm run start:dev`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `git push heroku main`
