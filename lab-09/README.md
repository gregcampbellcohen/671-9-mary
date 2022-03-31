# Module 09 Lab Assignment

## Table of contents

<!-- TOC -->

- [Module 09 Lab Assignment](#module-09-lab-assignment)
    - [Table of contents](#table-of-contents)
    - [Wild Eye Adventures site map](#wild-eye-adventures-site-map)
    - [Data files](#data-files)
    - [Required specifications of the deliverable](#required-specifications-of-the-deliverable)
        - [How to submit the deliverable](#how-to-submit-the-deliverable)
        - [Example map and web page](#example-map-and-web-page)

<!-- /TOC -->

The requirements of the map are listed below. All the tasks required to fulfill this assignment are documented within this and previous modules.

## Wild Eye Adventures site map

A national outdoor guiding service, Wild Eye Adventures, is looking for example site map that showcases a selected landform with elevation contours when zoomed in, but then show all landforms of the same type when zoomed out. Landforms might include a waterfall, pillar, arch, cliff, etc. 

The state, landform type, selected landform, contour interval, and base map style is your choice. This is a demonstration map that needs to be smooth and look razor sharp.

They want the map hosted on a web page that contains basic information about the selected landform. They request a picture (give appropriate credit) and a paragraph or two about the unique landform you have selected.


## Data files

* Landforms should be extracted from the National File on [Geographic Names Information System](https://geonames.usgs.gov/domestic/download_data.htm). Select any state. See lesson addendum for more information on this resource.
* **---OR---** use the provided file for point locations of U.S. named pillars located here: [map/pillars.geojson](map/pillars.geojson).
* After you select your landform to showcase, elevation data for your site map will be downloaded from the USGS NED 1/3 arc-second raster digital elevation model. This data can be accessed at the USGS 3D Elevation Program [usgs.gov](https://viewer.nationalmap.gov/basic/?basemap=b1&category=ned,nedsrc&title=3DEP%20View)

## Required specifications of the deliverable

1) The Mapbox map must fulfill the following requirements:

> * Select a landform type from the GNIS for a single state (or entire US for a challenge).
> * Pick an individual landform to showcase.
> * Landforms must have text labels that do not overlap the icon or symbol.
> * The web map must show elevation contours when zoomed into selected landforms. The zip contours Shapefile should not exceed 10 MB, so select a sufficiently small area for your site map.
> * The contours should fade out as you zoom to lower zoom levels.
> * Use the _lesson-map/map.html_ file you created in the lesson as a template.


2) The client has requested that the Mapbox map be embedded in a web page with more information about the showcased landform. Use the *lesson-map/index.html* file as a template.

> * Map needs to be an `iframe` element in the web page
>* A link should be provided to a full-screen version
> * The web page must have a meaningful title (both in the header title element and in the h1 element) and metadata about the author and data sources.
> * Web page must have (at least) one photograph of the landform and a short paragraph about the landform.
> * Contact information in footer must be tuned to you, the author.
> * The map page must be called "index.html" in the repo folder *lab-09/map*.


### How to submit the deliverable

Commit and push your final project to the lesson repository. Submit the repo URL to Canvas, e.g, _https://newmapsplus/map671-module-09-username_


### Example map and web page

https://uky-gis.github.io/maps/us-arches/
