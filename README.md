This project is meant to use API calls to create a webpage for finding weather information, using HTML, CSS, and JavaScript.

Currently, this project uses the Google Maps JavaScript API and Tomorrow.IO API, as well the browserify, moment.js, node-fetch, and query-string packages retrieved from npm. 

index.html in the Pages folder is the webpage that is accessed by the user. InputProcess.js is the source code for the main JavaScript implementation, and bundle.js is formed from
applying the browserify package to InputProcess.js. bundle.js is the script that is loaded into index.html. More information on the specifics of the JavaScript implementation can
be found in the documentation of those two .js files.

Currently, the keys for both the Google Maps JavaScript API and Tomorrow.IO API must be added in to a file named keys.json in the root directory of the project. The file keys.json.dist shows an example of how this should be organized.

The webpage currently functions, but this is a work-in-progress. Listed below are some of the planned improvements and additions:

- Dynamically change the timezone based on the city given by the user.
- Allow the user the customize what information is shown and the timesteps used.
- Overhaul the look of the webpage with CSS.
