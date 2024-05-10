# PWA: Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This application is a web-based text editor that enables users to create and store notes or code snippets, regardless of their internet connection status. It incorporates service workers and Cache APIs to ensure full functionality even in offline mode. Users can access previously visited pages, enhancing its usability when offline.

## Heroku Launch 
https://peaceful-tor-83220-5c21f77e22cc.herokuapp.com/


## Table of Contents

* [Installation](#installation)
* [Acceptance Criteria](#asseptance-criteria)
* [Contribution](#contribution)
* [Github](#github-repo)
* [License](#license)

## Installing the PWA

* Root directory run npm install 
* cd into /client run npm run build followed by npm install
* cd to /server run npm install followed by npm start

## Acceptance Criteria

GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application

## Contribution 
https://www.youtube.com/watch?v=WbbAPfDVqfY
used this as reference to help with project



## Github Repo

https://github.com/LONZEE/PWA

## License

This project is licensed under the terms of the MIT license.