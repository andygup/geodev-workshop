# ArcGIS Geodev Workshop

A place to learn how to build geo apps with the ArcGIS platform.

## Welcome

This repository contains a series of short labs that step you through in order.  The process described here uses [ArcGIS Online](http://www.arcgis.com) and 
[ArcGIS for Developers](http://developers.arcgis.com) accounts, tools, APIs and services, 
and does not require the installation of desktop software.


The process involves three steps:

1. [Data](#1-data) - Prepare data for your apps with [ArcGIS Online](http://www.arcgis.com).
2. [Design](#2-design) - Style maps and layers for your apps with the [ArcGIS Online Map and Scene Viewer](http://www.arcgis.com).
3. [Develop](#3-develop) - Use maps and layers in your apps with [ArcGIS templates, builders and APIs](http://developers.arcgis.com).

## Lab 0 - Setting up your environment

**Sign up for a free** [ArcGIS Developer subscription](https://developers.arcgis.com/en/sign-up/) - Your subscription allows you to download software, register apps, import data, create new services, store maps, perform spatial analysis and more. If you already have an [ArcGIS Organization subscription](http://www.arcgis.com/features/plans/pricing.html) (with at least publisher level permission) or access to ArcGIS Enterprise, that will work too.

> [Free public accounts](https://geonet.esri.com/groups/geodev/blog/2014/10/15/help-i-cant-get-into-developersarcgiscom) and Organizational 'User' accounts are *not* sufficient to complete the Labs.

## 1. Data
Creating and importing data interactively is a fast and effective way to prepare data for both prototype and production app development.

### Import Data 
[Start lab](https://developers.arcgis.com/labs/data/import-data/) where you use your own data (xls, gpx, GeoJSON, shapefiles) to create a layer.

* **Challenge** [Start lab](https://developers.arcgis.com/labs/develop/javascript/create-a-2d-map-with-a-layer/) to add the feature layer to a basemap. Use the feature layer you create above. 

### Create a New Dataset
[Start lab](https://developers.arcgis.com/labs/data/create-a-new-dataset/) to create an empty layer and then add data.

### Explore Layer Data
[Start lab](https://developers.arcgis.com/labs/data/explore-layer-data/) to learn how to view feature data using ArcGIS Online, the Map and Scene Viewers, and the REST API.

### Query Layers
[Start lab](https://developers.arcgis.com/labs/data/query-layers/) and learn how to build SQL and spatial expressions to get layer data.


## 2. Design
Learning to create web maps with great cartography is one of the most important steps to building effective mapping applications. Styling maps interactively can also be huge time-saver in app development.

### Create a Map in either 2D or 3D

Here you can choose to create either a [Web Map in 2D](https://developers.arcgis.com/labs/design/create-a-web-map/) or create a [Web Scene in 3D](https://developers.arcgis.com/labs/design/create-a-web-scene/). 

### Style Map

[Start lab](https://developers.arcgis.com/labs/design/style-a-web-map/) to learn how to use the Map Viewer to create meaningful visualizations. 

### Create a Web Map
[Start lab](https://developers.arcgis.com/labs/design/create-a-web-map/) to learn how to create a 2D web map that can be used within your own apps.

* **Challenge** [Start lab](https://developers.arcgis.com/labs/develop/javascript/display-a-web-map/) to display your web map using JavaScript. Use the ID from the web map you just created. 

### Configure a Popup

[Start lab](https://developers.arcgis.com/labs/design/configure-pop-ups/) to learn how to style popups in the Map Viewer.

### Style Layers with Smart Mapping 

[Start lab](https://developers.arcgis.com/labs/design/style-your-layers-with-smart-mapping/) to learn how to use smart mapping styles to work with multiple layers, perform simple calculations, and display data in meaningful ways.

## 3. Develop
One of the easiest ways to build an ArcGIS map app is to start with a web map, but you can also use the various
ArcGIS APIs and SDKs to build applications from templates or from scratch.

### Create Graphic

[Start lab](https://developers.arcgis.com/labs/develop/javascript/create-graphics/) to create a custom graphic.

### Search and Geocode

[Start lab](https://developers.arcgis.com/labs/develop/javascript/search-and-geocode/) to build a an app that can be used to search for places and find addresses.

### Access Private ArcGIS Online Layers

[Start lab](https://developers.arcgis.com/labs/develop/javascript/access-private-layers/) to learn how to work with private data.

### EXTRA CREDIT: Working directly with ArcGIS Online REST Services
Understanding how to interact with REST APIs, and ArcGIS Online REST Services in particular, is an important aspect of being a geospatial developer.
Whether you are developing directly against REST Services or simply doing troubleshooting on API, understanding the basics is am important skill.

[Start lab](https://developers.arcgis.com/labs/develop/rest/get-an-access-token/) to learn how to programmatically get an access token.

[Start lab](https://developers.arcgis.com/labs/develop/rest/get-coordinates-for-an-address/) to learn how to convert an address to a latitude/longitude coordinate.

[Start lab](https://developers.arcgis.com/labs/develop/rest/query-a-feature-layer/) to learn how to query a feature layer using the ArcGIS REST API.
* **Challenge** Review the Query capabilities in [REST API documentation](https://resources.arcgis.com/en/help/arcgis-rest-api/#/Query_Feature_Service_Layer/02r3000000r1000000/) and research the details of how the various parameters work.

[Start lab](https://developers.arcgis.com/labs/develop/rest/add-edit-and-remove-features/) and learn how to add, remove or delete features from a feature service.

## Data and Terms of Use

Please see [www.civicapps.org](http://www.civicapps.org/), [developer.trimet.org/gis](developer.trimet.org/gis) and [http://www.portlandoregon.gov/bts](http://www.portlandoregon.gov/bts) for the data terms of use.

## Licensing
Copyright 2017 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [LICENSE](./LICENSE) file.