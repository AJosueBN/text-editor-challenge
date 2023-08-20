# week-19-text-editor-challenge

Building a text-editor that runs in the browser that can meet the Progressive Web Application(PWA) criteria so it will be able to function online with an internet connection or offline and still be able to add text and save it to a database storage.

Technologies involved in this project include:

- PWA
- Manifest.JSON
- Service Worker
- Work-box web-pack plugins
- IndexedDB
- JavaScript

# Things implemented to the Text-Editor Application

GIVEN a text editor web application:

-WHEN the user opens the application in their editor
THEN they should see a client server folder structure
- WHEN the user runs `npm run build` and after `npm run start` from the root directory
THEN they find that the application should start up the backend and serve the client 
- WHEN the user runs the text editor application from my terminal
THEN they find that the JavaScript files have been bundled using webpack
- WHEN the user runs the webpack plugins
THEN they find that they have a generated HTML file, service worker, and a manifest file
- WHEN the user uses next-gen JavaScript in their application
THEN they find that the text editor still functions in the browser without errors
- WHEN the user opens the text editor
THEN they find that IndexedDB has immediately created a database storage
- WHEN the user enters content and subsequently clicks off of the DOM window
THEN they find that the content in the text editor has been saved with IndexedDB
- WHEN the user reopens the text editor after closing it
THEN they find that the content in the text editor has been retrieved from  IndexedDB
- WHEN the user clicks on the Install button
THEN they download the web application as an icon on their desktop
- WHEN the user loads the web application
THEN they should have a registered service worker using workbox
- WHEN the user has registered a service worker
THEN they should have the static assets pre cached upon loading along with subsequent pages and static assets
