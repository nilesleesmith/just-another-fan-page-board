# Just Another Fan Page Board

A fan page with user accounts, a profile page, and a message board backed by MongoDB.

## Overview

This project combines a fan page with a user authentication system and a message board. Users can sign up, log in, view their profile, and interact with messages stored in the database.

The application uses Express to handle server requests, EJS to render pages, Passport for authentication, and MongoDB to store user and message data.

## Features

- User registration and login
- Local authentication with Passport
- Profile page for authenticated users
- Submit and display messages
- Upvote, downvote, and delete message controls
- Session-based authentication

**Note:** The voting functionality needs correction and testing. The current downvote route changes the upvote count instead of updating the downvote count.

## Technologies

<p>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" title="HTML">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" title="CSS">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://nodejs.org/" title="Node.js">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://expressjs.com/" title="Express">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://www.mongodb.com/" title="MongoDB">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://www.passportjs.org/" title="Passport">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/passport/passport-original.svg" alt="Passport" width="40" height="40">
  </a>
</p>

- [EJS](https://ejs.co/)
- [npm](https://www.npmjs.com/)

## Run Locally

**Requirements:** Node.js, npm, and a MongoDB database.

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Open the project directory:

   ```bash
   cd just-another-fan-page-board
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Configure the MongoDB connection in `config/database.js` to use your own database. Do not commit database credentials.

5. Start the server:

   ```bash
   node server.js
   ```

6. Open [http://localhost:8080](http://localhost:8080) in your browser.

## Security Notes

Before deploying this application, move database credentials and the session secret out of the source code and into appropriate environment configuration. Review authentication, session settings, and message authorization before making the application publicly accessible.

## Live Site

Coming soon!

## Screenshots

Coming soon! Desktop, tablet, and mobile screenshots will be added here.