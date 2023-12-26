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