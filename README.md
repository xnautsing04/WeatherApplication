This project is meant to use API calls to create a webpage for finding weather information, using HTML, CSS, and JavaScript.

Currently, this project uses the Google Maps JavaScript API, Google Timezone API, and Tomorrow.IO API, as well the browserify, moment.js, node-fetch, and query-string packages retrieved from npm. 

index.html in the Pages folder is the webpage that is accessed by the user. InputProcess.js is the source code for the main JavaScript implementation, and bundle.js is formed from
applying the browserify package to InputProcess.js. bundle.js is the script that is loaded into index.html. More information on the specifics of the JavaScript implementation can
be found in the documentation of those two .js files.

Currently, the keys for both the Google Maps JavaScript API and Tomorrow.IO API must be added in to a file named keys.json in the root directory of the project. The file keys.json.dist shows an example of how this should be organized.

The user can change between a 7-day forecast and 24-hour forecast, which is done with a CSS styled checkbox and changing the forms between none and inline-block styles, which only shows up after a valid city and state combination is entered and submit is pressed. The information presented includes precipitation, temperature, and wind details.
