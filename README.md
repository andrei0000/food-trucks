Food Trucks Demo
================

Goal
--------------------------

The goal of this demo project was to create a service that tells the user what types of food trucks might be found near a specific location on a map,
using the data from [DataSF: Food Trucks](https://data.sfgov.org/Permitting/Mobile-Food-Facility-Permit/rqzj-sfat), also an appropriate UI (front-end) should be available.

Solution
--------------------------
The solution features front-end and back-end parts utilizing Bootstrap (for front-end) and Spring Boot (for back-end).
A user opens an app in a browser and can specify a desired location (by clicking on a map) and a desired search area in miles (using appropriate slider).
A UI part contacts our back-end service which in turn queries the food trucks database based on the criteria supplied by the user.
Food trucks positions matching the specified critera are displayed on a map.
User can click on a desired truck marker in order to see an additional information about the specific truck (truck type and food items it delivers).

Installation
-----------
TBD

Usage
-----------


App demo
-------
You can see this demo project [in action]().

Trade-offs
---------

If I'd have more time to spend on a project I would, at least:
* Add API key based security to the services
* Add caching support for the data retrieved from DataSF.
* Host JS/CSS on jsDelivr.
* Move google-api key definition from index.html to the settings file.
* Enhance the UI (by making it more intuitive, adding a list of trucks that match the specified criteria, show the spinner if query takes too long to process etc.)
* Create appropriate tests for front-end.
* Add support for a fine filtering for radius search instead of a search by a square.

