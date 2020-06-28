# Node.js Authentication

This is basic authentication app created using Node.js and Passport used to authenticate user for sign in.

In this we used two strategy 
1. Passport Local Stretagy (For local authentication)
2. Passport google-oauth Strategy (For Social authentication)

## Directory Structure:

1. assets folder: It contains all the static files like css, js, images.

2. config: All the configuration files like
   - mongoose.js
   - middleware.js
   - passport-local-strategy.js
   - passport-google-oauth2-strategy.js

3. Controller: It contains all the controllers for routes 
   - home_controller.js
   - users_controller.js
   
4. Models: Schemas 
   - user.js
   
5. Routes: files for routing the user request to the appropriate controllers
   - index.js root file
   - users.js
   
6. Views: It contains all the ejs files that has to render after a success request accordingly.

## Starting the project:

1. Download as zip or clone and extract it to your system.
2. Open folder.
3. Open terminal and make the project folder as your current directory
4. Input following commands:

```
npm install express
npm install ejs
npm install mongoose
npm install passport
npm install connect-flash
npm install connect-mongo
npm install cookie-parser
npm install express-ejs-layouts
npm install express-session
npm install node-sass-middleware
npm install passport-local
npm install passport-google-oauth
npm install crypto
```
5. To start the server, use command: npm start
6. Go to https://localhost/8000 on your browser to use the application
7. Now you are good to go.
