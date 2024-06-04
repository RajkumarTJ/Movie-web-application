# Movie Library Web Application
## Setup Guide

To deploy the Movie Library Web Application locally, start by downloading Node.js from [here](https://nodejs.org/en/download/). Node.js includes npm, which is necessary for managing project dependencies.

## Installation Steps
1. Open your terminal and execute `npm install` to install all dependencies.
2. Launch the application with `npm start`.
3. Access the application at [http://localhost:8000](http://localhost:8000) via your browser.

###  Project Setup:
## 1. Initializing the Project
Begin by initializing the project with `npm init`.

## 2. Installing Express
Install Express using `npm install express`.

## 3. Integrating EJS
Incorporate EJS by installing it with `npm install ejs`. Then, add the following lines to your `index.js` to enable EJS:
```javascript
app.set('view engine', 'ejs');
app.set('views', './views');
```

## 4. Adding Express-EJS-Layouts
Integrate Express-EJS-Layouts by installing it with `npm install express-ejs-layouts`. Add the following lines to your `index.js` to utilize it:
```javascript
const expressLayouts = require('express-ejs-layouts');
app.use(expressLayouts);
```

## 5. Utilizing Mongoose
Mongoose, a MongoDB object modeling tool, supports asynchronous environments. Install it with `npm install mongoose`.

## 6. Incorporating Cookie-Parser
For handling cookies, use `npm install cookie-parser`.

## 7. Implementing Passport
Passport.js is middleware for Node.js authentication. Install it with `npm install passport`.

## 8. Adding Passport-Local
Install Passport-Local using `npm install passport-local`.

## 9. Including Express-Session
For session management, install `npm install express-session`.

## 10. Integrating Connect-Mongo
To use MongoDB as the session store, install `npm install connect-mongo`.

## 11. Configuring Dotenv
Install `dotenv` with `npm install dotenv` for managing environment variables with a `.env` file.

###   Software Requirements :
1. Updated browser.
2. Node.js installed (Download it [here](https://nodejs.org/en/download/)).
3. Any preferred text editor.


