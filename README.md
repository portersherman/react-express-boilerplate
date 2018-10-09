# React-Express-Boilerplate
Here you'll find a simple, bare bones React/Express app ready for development.

## /fe
This folder contains all the frontend files, as suggested by the name. 
You can either write all your css in src/css/App.css, or use SASS and separation of concerns to compile .scss files from component directories to /src/css/App.css.
I would recommend using superagent to make backend requests, but I leave that choice up to the developer.
Run "npm start" to develop.

## /be
The backend is located here. The code is very lightweight, since it only needs to route requests and possibly make database calls.
Run "npm run dev" to develop.

## Deploying
When it comes time to ship the app, create a production build from /fe and move the resulting /build/ folder to /be
Running "npm start" should then serve this build.
