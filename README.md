# Asynchronous-Code
Week9: Asynchronous Code

I. File list
------------
Asynchronous Code - Microsoft Word Document

index_html_AddMapMarkers- HTML File

addMarkersToMap - JavaScript File

style_AddMapMarkers - CSS File

index_html_AddAnimationToMaps - HTML File

addAnimationtoMaps - JavaScript File

style_AddAnimationToMaps - CSS File


II. Concept
----------
The word document discusses asynchronous coding and provides a simple example. It also talks about promises and async await functions.

The index_html_AddMapMarkers- HTML File allows you to use the MapBox API and put custom markers at your chosen locations on a map. Please download all files and put in the same folder.

The addMarkersToMap - JavaScript File allows you to use a token to access the MapBox API. You must sign up for an account and generate a TOKEN and enter it into the JavaScript code for this to work. I have zeroed out my token with XXXXX out for security reasons. You can get an account and sign up for your own personal token at MapBox here: https://www.mapbox.com/ Then you enter your token in the first JS function here: 

function createMapMarker() {
  
  // TODO: add your own access token
  
  mapboxgl.accessToken = XXXXX
  
Once your token is loaded into the JS file you can drag and drop your HTML file into an empty browser window and your custom marker will apear at the desired location. You can change the coordinates or add as many locations as you like.
  
The style_AddMapMarkers - CSS File allows you to style your markers.
  

III. Future Improvements
----------
Expand on asynchronous coding and show project examples.

IV.  License
----------
The source material for this repository contains information and code from the MITxPRO Full Stack Development with MERN 32 week bootcamp course.
As a student in the course, I have participated in reading the course materials and created my own code throughout all of the course projects. As a result I have provided my own additions, comments, material and code to the repositories along the way.
