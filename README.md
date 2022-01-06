This project is meant to use API calls to create a webpage for finding weather information, using HTML, CSS, and JavaScript.

Currently, this project uses the Google Maps JavaScript API, Google Timezone API, and Tomorrow.IO API, as well the browserify, moment.js, node-fetch, and query-string packages retrieved from npm. 

index.html in the Pages folder is the webpage that is accessed by the user. InputProcess.js is the source code for the main JavaScript implementation, and bundle.js is formed from
applying the browserify package to InputProcess.js. bundle.js is the script that is loaded into index.html. More information on the specifics of the JavaScript implementation can
be found in the documentation of those two .js files.

Currently, the keys for both the Google Maps JavaScript API and Tomorrow.IO API must be added in to a file named keys.json in the root directory of the project. The file keys.json.dist shows an example of how this should be organized.

This webpage is not finished and refinements are still being worked on as of the last update to GitHub.
