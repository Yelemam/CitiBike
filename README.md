# CitiBike

![citibike_NY](https://github.com/user-attachments/assets/1d9d2ea1-3d69-4d6e-a589-86b4822ad17b)

# Citi Bike Station Map Visualization

# Project Overview

This project is a web-based visualization of Citi Bike stations using Leaflet.js and D3.js. It pulls data from the Citi Bike API to display the locations of bike stations in New York City on an interactive map. The map provides a visual representation of station locations and details like the station's name and capacity.

# Project Structure

The project consists of three main files:
1. index.html: The core HTML file that sets up the structure of the web page and links to external libraries like D3.js and Leaflet.js.
2. style.css: A CSS file that contains the styles for the web page, ensuring that the map and its elements are displayed correctly.
3. logic.js: A JavaScript file that contains the logic for creating and displaying the map, fetching data from the Citi Bike API, and adding markers to the map.

# Technologies Used

1. HTML/CSS: Used for structuring and styling the web page.
2. JavaScript (D3.js and Leaflet.js): Used for fetching data and creating interactive map visualizations.
3. Citi Bike API: Used to obtain real-time information about Citi Bike stations.

# Setup Instructions

1. Clone the repository: Download or clone the project files to your local machine.
2. File Organization: Ensure that the CSS file (style.css) is located in the static/css folder and the JavaScript file (logic.js) is in the static/js folder, as referenced
   in the index.html file.
3. Open the HTML file: Open the index.html file in a web browser to view the interactive map.
4. Internet Connection: Ensure you have a stable internet connection since the project fetches live data from the Citi Bike API.

# How It Works

1. Data Fetching: The JavaScript file (logic.js) fetches data from the Citi Bike API using D3.js to retrieve information about the bike stations.
2. Map Creation: A map is created using Leaflet.js, centered on New York City.
3. Marker Generation: Markers are added to the map to represent each bike station. Clicking on a marker displays a popup with the station's name and capacity.

# Future Enhancements

1. Additional Layers: Add more layers to visualize bike availability or other relevant data.
2. Search Functionality: Implement a search feature to find bike stations by name or location.
3. Improved Styling: Customize the map's appearance and make the UI more user-friendly.

# Dependencies

1. D3.js
2. Leaflet.js
3. Internet access to fetch data from the Citi Bike API

# Acknowledgments

1. Citi Bike: For providing the data used in this project through their open API.
2. Leaflet.js and D3.js Communities: For their comprehensive documentation and tutorials, which greatly assisted in the development of this project.
3. OpenStreetMap Contributors: For the map tiles and data used in visualizing the bike stations.
