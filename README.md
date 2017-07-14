# d3.geomap

![npm package version](http://img.shields.io/npm/v/d3-geomap.svg)
![npm package license](http://img.shields.io/npm/l/d3-geomap.svg)

**d3.geomap** is designed to be a
[reusable](http://bost.ocks.org/mike/chart/) geographic map for D3. In its current stage it consists of a class to create plain maps `d3.geomap()`
and one for choropleth maps `d3.geomap.choropleth()`.

Refer to the [documentation on how to use d3.geomap](http://d3-geomap.github.io/) and to download a bundle that contains minified versions of d3.geomap and its dependencies as well as TopoJSON files for creating world and individual country maps.

## Pre-install
1. Node has been install in the local machine. https://nodejs.org/en/download/
2. Ruby has been install in the local machine. https://www.ruby-lang.org/en/downloads/

## Tips
If having issue running npm install, try to configure a web-proxy

    $ npm config set proxy http://proxy.company.com:8080
    $ npm config set https-proxy http://proxy.company.com:8080

## Start the development server
    
    $ npm install gulp
    $ npm install
    $ gulp

Open `http://localhost:8000/gdp/` in a browser and choose 'index.html' to view the maps.

## Map Showcase

In order to complete this project, i use below sources of github project to complete it.
1. https://github.com/deldersveld/topojson/tree/master/continents 
   This is to display into a continent level
2. https://d3-geomap.github.io and https://github.com/yaph/d3-geomap
   This is purely an enhance version build on top of d3.js

Library use.
1. d3.js      - This library is use to display data using 
2. d3.geomap  - Library for creating a geographic maps. 
3. topojson   - An extension of GEOJSON that encodes topology. It is lighter than GEOJSON.
4. gulp       - A javascript task runner to automate task such as minifying JS and CSS, less/sass compilation, copying modiying files to output directory and to create a lightwight server

