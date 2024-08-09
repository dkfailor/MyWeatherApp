# MyWeatherApp
Local Weather Web Page and Android APK.  All of the source code is my own except for the external weather data from https://wttr.in. The author of the weather source has a repo on GitHub that you can review if you are interested.

# Overview
This web page pulls in external content and packages it with added functionality.  I also took the same code (html/css/js) and created an Android APK app.

# Process
1. I was looking at various means to pull in external third-party content to create a practical web page.  My preference was not to use extra modules like React.js or Angular.js.  I decided to use an iframe and modify it with CSS and JavaScript.  My source code is included in this repository as both an index.html and a pdf file.  I also wanted to make this page and the Android app as self-contained and fast loading as possible so I chose to use SVG image files instead of JPG files.  I created the clouds SVG using an online source and I created the sun SVG with Inkscape.
2. After I completed the web page app to my own satisfaction, I decided to convert it into an Android app.  I don't have time to create it from scratch using the Android SDK so I used an online app creator as 'proof of concept'. It turned out okay but I'm not completely satisfied with the visual result. Also, the online version of the app adds advertising from the online web app creator program, and it reports back to the company the location where it was installed. I reverse-engineered the Manifest.xml file and included it in this repo so you have an idea what resources and permissions it needs.
3.  My next step will be to install Linux apk software and recreate this weather APK myself. I used to sell apps on the Google Play store so I may upload this one as well.
4.  Please look at the source code and run the index.html file.
5.  Thanks!

# Usage
Load the index.html file in your browser and enter your city and state.  Then click the button and it will show you the weather forecast for your location.  If your location is not found, use the nearest larger city.
