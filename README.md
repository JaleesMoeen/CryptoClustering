# CryptoClustering
 Cryptocurrency clustering is the process of categorizing cryptocurrencies into groups based on shared characteristics or features, aiming to reveal patterns and similarities within the cryptocurrency market.


### CyrptoClustering Unsupervised Machine Learning

Hi, let's find out out optimized clusters through implementation of elbow method, K-means and PCA algorithms.


![Alt text](images/1_crypto.png)


### 1 Introduction 

Through innovative data analysis and visualization techniques, Cryptoclustering aims to provide valuable insights, aiding investors, analysts, and researchers in navigating the complexities of the ever-evolving cryptocurrency landscape.


![Alt text](Images/2_usgs.png)



### 2 Prerequisites

Before you begin, ensure you have the following installed:

HTML, CSS ( for structure and style web page)

JavaScript ( for dynamic behavior)

D3.js ( for data manipulation)

Leaflet.js ( for interactive maps )


### 3 Data Sources

We used the two data scources:

To visualize an earthquake dataset [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)

To visualize realtionships between tectonic plates and seismic activities [Tectonic Plates Dataset](https://github.com/fraxen/tectonicplates)


![Alt text](Images/3_world_map.jpg)


### 4 Features

Leaflet-based interactive map.

Visualization of earthquake data based on longitude and latitude.

Data markers reflecting earthquake magnitude (size) and depth (color).

Popups with additional information about each earthquake.

Map legend providing context for the data.

Visualization of tectonic plates dataset.

Multiple base maps and overlays.

Layer controls for independent toggling of datasets.


### 5 Execution with D3.js and Leaflet.js


We performed the following operations for the logic.js in both the folders "Leafelt-Part-1" and "Leafelt-Part-1":

- Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

- Include popups that provide additional information about the earthquake when its associated marker is clicked.

- Create a legend that will provide context for your map data.


Additionally, to plot the tectonic plates and seismic activities, we added the follwoing operations:


- Plotted the tectonic plates dataset on the map in addition to the earthquakes.

- Added the gray sclae, outdoor , and satellite base maps.

- Put each dataset into separate overlays that can be turned on and off independently.

- Added layer controls to your map.

### 7 Earthquake Data Visulaizations

At a glance , there is the earthquake visualiations where the set view is pinned at Ontario, Canada.


![Alt text](Images/4_earthquakes_visualizations.png)


### 8 Visulaizations of Relationship b/w Tectonic Plates & Seismic Activities

Below is a glimpse of how the realtionship between tectonic plates and seismic activities looks like:


![Alt text](Images/5_tectonic_plates.png)


### 9 Usage

We can visualize the data on the map for earthquakes details and the relationships between tectonic plates and seismic activities.


### 10 Deployment

This dashboard is deployed on [GitHub Pages](https://jaleesmoeen.github.io/USGS_Earthquake_Visualizations/).


## Author

## [Jalees Moeen GitHub](https://github.com/JaleesMoeen)
