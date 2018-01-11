# Weather Forecaster Web App

This web application is a college project that provides a 'forecast' of the weather in Dublin over a fixed 5 day period (Oct19-23 2017) using data from local JSON files, which were provided by openweathermap.org. It's written in pure JavaScript (no frame works), HTML and CSS.

To run the web app, open 'index.html' in a web browser.



Note that the Google map (via API), Google font (source sans pro), Font Awesome icons and Openweather icons are linked in from the corresponding external URLs, so proper display requires an internet connection.



The app uses a constant base html layout: header (title, display panel) + forecast period form + footer. The display panel is updated by calling (on click of 'submit' button) a JavaScript function in '/js/siteScript.js' to show the data from 'daily.json'. The updated panel provides a new button(s) to call a futher update that provides the detailed weather information ('detailed.json') for the selected day. See '/js/siteScript.js' for details.



The forecast selector form remains at the bottom of both the daily and detailed views to allow further forecast choices to be made. There's a triangular button over the footer to skip back to the top of the current page. Clicking on the logo in the title (top) banner or the 'FORECASTER' text in the footer will bring back the homepage content.