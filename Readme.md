# Overly Simplified Rest API
This is not a recommend setup. But it a quick learning and test configuration with nodemon server auto restart for convience. 
### Prerequisite
1. Install NodeJS

### Express tutorial part 1
http://expressjs.com/en/starter/installing.html

1. make folder for app
1. open terminal in folder
1. Run and complete `npm init` (use `app.js` as entry point)
1. create `app.js` file
1. Run `npm install express --save`

### Nodemon

This auto restarts server on save. Below is a minimal setup.

https://www.npmjs.com/package/nodemon
1. Run command: `npm install --save-dev nodemon`
1. Run command: `npx nodemon ./app.js localhost`

### Express tutorial part 2
http://expressjs.com/en/starter/hello-world.html

1. Open empty `app.js` file
1. Copy the script fromt the above tutorial link and paste it into `app.js` 
1. Save `app.js` and try the url below

Link `localhost:3000`

Now you have a starter API server!

### Adding a Database
Database server are seperate software servers which run on their own ports. They can be setup on seperate computers and conneceted to the app over a network, preferably over a private network to keep data transfer secure.
1. Download and install your favorite relational database (examples: postgres or mysql)
1. Get and install a npm database driver for your favorite database type. This is a library that helps with managing database connections and making requests.

Exercise:
1. Send a test connection from the server to the database to get the version. Then output it serverside with `console.log()`.
1. Return the database version retrieved from the database to the client as a Get Response endpoint.