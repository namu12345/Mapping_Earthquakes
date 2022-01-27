# Mapping_Earthquakes

_An interactive earthquake map with JavaScript and Leaflet_

**Note:** Final documents are stored in Earthquake_Challenge directory. Please find the explanation of the files below. Code needs an API Key from Mapbox in order to run. The API key is not included for safety reasons. Other files (i.e. Earthquakes_past7days, Simple_Map and json files) are included because of the detailed procedure of working with Mapbox, Leaflet and GitHub branching.

## Project Overview
### Purpose
For this project I am creating an interactive map that shows the latest earthquake activity around the world. Maps allow us to explore, understand and make decisions about our world. Providing data-driven storytelling on disasters around the world and building insightful data visualization with interactive features is a valuable addition to the knowledge and awareness of planet Earth.

The map of earthquakes around the world contains:

- Fault lines of tectonic plates.
- Earthquakes of the past 7 days.
- Major earthquakes of magnitude above 4.5.
- Three different map styles:
    - Street view.
<img width="1147" alt="Screen Shot 2022-01-23 at 9 35 53 PM" src="https://user-images.githubusercontent.com/92283185/151395461-19a0de97-ad70-42c4-b1ea-c901c0b46d22.png">


    
    - Satellite view.
<img width="1155" alt="Screen Shot 2022-01-23 at 9 34 43 PM" src="https://user-images.githubusercontent.com/92283185/151395674-506f0c0f-1a8b-40bb-b8fc-6eb831bec1a1.png">

    
    - Dark view.
<img width="1146" alt="Screen Shot 2022-01-23 at 9 35 10 PM" src="https://user-images.githubusercontent.com/92283185/151395787-b200c97f-7450-405e-aff0-0c935420c352.png">

    
- A popup marker with information about the location and magnitude of the earthquake.
![image](https://user-images.githubusercontent.com/92283185/151395968-e465cdd8-f1eb-4aec-8b76-0475a7731fab.png)

- The diameter and the color of a marker reflect the strength of the earthquake (darker color with larger diameter represent earthquakes with a higher magnitude).
![image](https://user-images.githubusercontent.com/92283185/151396133-c06d5e91-6182-42e7-b7bc-b7f3a3676356.png)

- A legend with the context for the map.

![image](https://user-images.githubusercontent.com/92283185/151396222-f31a9e4b-52eb-48f5-8780-32ec497e8118.png)


### Background
Creating interactive maps is supported by specifically developed tools. For this project I used the following:

**Mapbox API**, an open source mapping platform for custom designed maps.

**Leaflet**, a JavaScript library, designed to build the web mapping applications.
![image](https://user-images.githubusercontent.com/92283185/151396428-9d608066-bb9a-43a8-975c-07d1af4e3310.png)


GeoJson files that are specifically design to host geographical information. GeoJson files are the industry standard for representing simple geographical features, such as points, linestrings and polygons and non-spatial attributes, such as magnitude of the earthquake, hurricane strength, hail size, elevation, etc.

## Resources
### Data Source:

- [GeoJson file for Tectonic Plates retrieved from GitHub repository](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- [GeoJson file for Earthquakes for the past 7 days retrieved via API call from USGS website](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
- [GeoJson file for Major Earthquakes (M4.5+) for the past 7 days via API call from USGS website](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
### Software:

- [Mapbox API challenge_logic.js](https://github.com/namu12345/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js)
- VS Code and Chrome Developer Tools
### Languages:

- JavaScript
- [HTML](https://github.com/namu12345/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html)  
- [CSS](https://github.com/namu12345/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css)
### Libraries:

D3, Leaflet
