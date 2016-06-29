#README

###Files###
The application itself is located within `index.html`. The 'js' folder contains the source code for the Knockout front-end framework, `map.js` which calls a number of Google Map and Places API functions, and `list.js` containing the ViewModel allowing us to update and retrieve data directly from HTML elements in `index.html`. In the 'css' folder there is `style.css` which moulds the aesthetics of the application, and also includes media queries allowing it to function on desktop, tablet, and mobile devices.

###How to Use###
The Museums Map application allows users to access information about popular museums near their current location, or anywhere around the world. This information is presented graphically by markers on the map, or textually through a list view. Clicking on the marker or associated list item will cause an information window to open with additional details such as Wikipedia descriptions. Information can be manipulated further by typing into an input box which will filter markers and associated list items according to the terms entered. When the user first opens the application, it will attempt to display museums within the radius of their immediate location, but users can also browse any location around the world by entering terms into the location input. Users can also navigate using the graphical map, and press a refresh button to reveal nearby museums, if any.