# pwa-edits

## Description 
***
This PWA challenge involves a browser-based text editor that meets PWA criteria and features data persistence techniques to function offline. The project utilizes the idb package, which is a lightweight wrapper around the IndexedDB API, to store and retrieve data. 

## Usage
***
To use this app, you'll need to have Node.js installed on your computer. Once you have those installed, you can follow these steps:


Install the necessary dependencies, please use:
```
npm install
```

To start the development server, run the following command:
```
npm run start:dev
```
To start the production server, run the following command:
```
npm start
```




## User Story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
## Acceptance Criteria
```
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
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```
## **App URL:**

[Deployed Site <-- CLICK ME!](https://polar-peak-54118.herokuapp.com/)


![screenshot](./assets/Screenshot%202023-04-29%20215301.png)


Sources: 

blogrocket:
- https://blog.logrocket.com/how-to-build-a-progressive-web-app-pwa-with-node-js/

Stackoverflow:
- https://stackoverflow.com/questions/70178726/webpack-manifest-json-not-found

google/developer.chrome:
- https://developer.chrome.com/docs/workbox/modules/workbox-precaching/
- https://developer.chrome.com/docs/workbox/modules/workbox-recipes/

ChatGPT, 
Instrcutor: Bassie B., 
TA: Ethan D.,
Tutor: Jacob C. 