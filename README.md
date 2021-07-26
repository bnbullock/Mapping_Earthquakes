# Mapping_Earthquakes


## Project Overview

Working with our clients, we have been able to create a webpage with 2 different maps along with an earthquake overlay showing world wide earthquakes that have taken place in the last 7 days. Our clients are now interested in comparing the locations of earthquakes to the earth's tectonic plates. They would like to add a map overlay with this information. They would also like a second selection that allows for only viewing earthquakes that have a magnitude greater than 4.5 on the map. And finally they think it's a good idea to add a third map to the webpage that allows for additional flexibility moving forward.

- Deliverables:
  1. Create overlay with Tectonic Plate Data
  2. Create overlay with Major Earthquake Data
  3. Create an additional Map
------------------------------------------------------------------------------------------------------------

## Resources
- Software: Visual Studio Code 1.56.2, JavaScript & Markdown shells within VS Code
- Browser : Google Chrome v91.0.4472.124 
- Libraries: Bootstrap v4.0, d3 v4.11.0, Leaflet v1.7.1, Mapbox v8.0
- Data: OpenStreetMap, https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php, https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json
------------------------------------------------------------------------------------------------------------

## Results

- The final map which meets all deliverables is shown below. The displayed map is using the "streets" view and includes all overlays. The selection panel allows choices of 3 different selectable maps-streets, satellite and dar mode views were designed to meet the expectations of our clients. The legend was augmented to allow for all earthquakes and major earthquakes to be displayed cohesively. Major earthquakes uses 3 color panels while 5 color panels are used for all earthquakes.

![Website](/Earthquake_Challenge/static/images/map.png)


### Selection
- The Panel showing below allows the user to select from the six different options or mix and match as may be required.

![Website](/Earthquake_Challenge/static/images/panel.png)


### Legend
- This chart shows the final legend panel and associated color codes.

![Website](/Earthquake_Challenge/static/images/legend.png)


### Overlays
- Tectonic Plates - shown below, overlayed on the map with a weighted line of 1.

![Website](/Earthquake_Challenge/static/images/tectonicmap.png)

- Dark map option with all Earthquakes and major earthquakes measuring more than 4.5 in magnitude in the past 7 days are displayed along with tectonic plates.

![Website](/Earthquake_Challenge/static/images/darkmap.png)

- Satellite map option shown with all major earthquakes above magnitude 4.5 in the past 7 days.

![Website](/Earthquake_Challenge/static/images/majorEQ.png)
------------------------------------------------------------------------------------------------------------

## Summary Analysis

- The display results have met the deliverables as outlined above. Tectonic plates were added as a selectable overlay, major earthquakes with 4.5 magnitude or higher has a separate selectable overlay and the added map with "dark" mode added as a third map option. All layers can be added or removed using the selectable panel located at the top right of the webpage. Additional changes can be tweaked if our clients need specific color combinations or additional features on any of the maps.