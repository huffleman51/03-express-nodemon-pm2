Tutorial that I followed is [here](https://github.com/verekia/js-stack-from-scratch/blob/master/tutorial/03-express-nodemon-pm2.md#readme).

## What I learned in this module

1. Express is by far the most popular web application framework for Node.
1. All static content goes into the /public folder.  This folder is referred to as /static which can be configured in the index.js
1. The src/shared folder are for files shared with both client and server applications 
1. The src/client folder is used to store any client files
1. The src/server folder is for server files.  index.js is the default node file to execute.
1. The render-app.js file just returns html to be rendered
1. Nodemon is a utility to automatically restart your Node server when file changes happen in the directory. Or can be used to automatically run tests when any file is changed
1. PM2 is a Process Manager for Node. It keeps your processes alive in production, and offers tons of features to manage them and monitor them.
1. One of the main features of Babel is to take a folder of ES6 code (usually named src) and transpile it into a folder of ES5 code (usually named lib).
1. "prod:build": "rimraf lib && babel src -d lib --ignore .test.js"
1. cross-env makes it so you can have a single command without worrying about setting or using the environment variable properly for the platform. 
1. 
