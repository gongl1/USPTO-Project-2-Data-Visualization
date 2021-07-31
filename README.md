# project2-heroku

https://www.uspto.gov/web/patents/classification/selectnumwithtitle.htm

Steps to run the app:
1. Download the repo folder. 
2. Down the 3 json data files from this link https://claycorp-my.sharepoint.com/:f:/r/personal/gongl_claycorp_com/Documents/uspc?csf=1&web=1&e=6Aof5W Replace the 3 json files under project2-heroku-main\project2-heroku-main\ETL_extension_flask\ with the 3 new json files you just downloaded.
3. Open project2-heroku-main\project2-heroku-main\ETL_extension_flask\app.py, Open in Intergrated Terminal, type in python app.py in termial. This will provide the data source routes. http://127.0.0.1:5000/
4. Point to project2-heroku-main\index.html, right click for Open with Live Server (http://127.0.0.1:5500/index.html) or type in python -m http.server in terminal (http://127.0.0.1:8000/index.html). 



## Background

![1-Logo](Images/FrontPage.PNG)

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.



Your first task is to visualize an earthquake data set.

1. **Get your data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * Your data markers should reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

   * **HINT** the depth of the earth can be found as the third coordinate for each earthquake.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for your map data.

   * Your visualization should look something like the map above.


## Rubric



- - -

� 2021 Liang Gong. All Rights Reserved.
