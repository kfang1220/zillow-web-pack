#Z illow WebPack Setup

## What this repo does
Creates a new directory with the following:
Generates dynamic HTML file
Bundles JS/CSS files and injects into HTML
Handles images and files and creates references

## Testing
Fork/Clone
npm install
delete any dist/image folders in root directory and index.html
npm run build
start a server and the html page should be generated with appropriate files
you can also do npm run start but the image will not load, the above option does load the image

## ToDo
Find a way to avoid recreating bundle/css/html files in development
Test SVG