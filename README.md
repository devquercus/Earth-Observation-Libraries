- [Some introduction](#some-introduction)
  - [Python anaconda](#python-anaconda)
    - [Python libraries](#python-libraries)
- [Python Earth Observation Libraries](#python-earth-observation-libraries)
  - [General data analysis tools](#general-data-analysis-tools)
  - [For vector data](#for-vector-data)
  - [For raster data](#for-raster-data)
  - [Vector and raster](#vector-and-raster)
  - [Machine learning libraries](#machine-learning-libraries)
  - [Download and process remote sensing data](#download-and-process-remote-sensing-data)
  - [Visualisation tools](#visualisation-tools)

# Some introduction
Earth observation data is rapidly increasing. This is happening due to the evolution of remote sensing platforms, and breakthroughs in data collection and storage systems during the last years. 

Earth observation data, provide detailed and at large-scale maps of weather patterns, vegetation health, atmospheric pollutants, soil moisture and rock types, among others. Moreover, earth observation data is used to map species distributions and disease risks in natural and agricultural areas.

Today, according to the [union of concerned scientists](https://www.ucsusa.org/resources/satellite-database), there are more than 800 earth observation satellites in orbit, which they collect about few TBs of data each day.

Tha analysis of all these data in order to extract usefull information from them is crucial and demanding task. 

Below you will find a list of the most frequently used tools for earth observation data analysis. 

Most of the tools you would probably need for the analysis of earth observation data, are basicly libraries for programming languanges such as python, R or Javascript. In some cases you might also need a gui software. 

## Python anaconda
First of all you must install in your machine the python programming language. The best way to install python is by using the [Anaconda python environment](https://www.anaconda.com/products/individual). There are versions for mac, windows and linux, so you won't have any problem installing this whatever operating system you use. I'm not going to describe here how to install this on your machine, there is plenty information online on how to do this. 

Anaconda is frequently used for data analysis so, it is not a surpice that this is also the most usefull tool for earth observations data analysis, too. 

The reason we suggest to intall Anaconda, is basicaly the ability you have to install user level of the version of python of your choice. Morover, to eliminates the headaches of trying to figure out which version of package X is compatible with which version/release of package Y. Additionally you will be able to install and update libraries completely independent of the system libraries or admin privileges. 

### Python libraries
Installing just anaconda will do the job for you. You need to install also some libraries in order to be able to process earth observation data. Below is a list with the most commonly used libraries in earth observation data analysis. We are not going to examine those libraries in detail, but rather we just list them here. In following articles we are going to describe in more detail and how you can use them in conpination to extact usefull information. 

# Python Earth Observation Libraries
Below is an attempt to document and list the most commonly used python libraries used for Earth Observation Data Analysis. This list is a live document and it will be updated versions [here](https://github.com/devquercus/Earth-Observation-Libraries). 

Feel free to form and contribute.
## General data analysis tools

* [pandas](https://github.com/pandas-dev/pandas): is a package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive.
## For vector data
* [geopandas](https://github.com/geopandas/geopandas): is a project to add support for geographic data to pandas objects. It currently implements GeoSeries and GeoDataFrame types which are subclasses of pandas.Series and pandas.DataFrame respectively. GeoPandas objects can act on shapely geometry objects and perform geometric operations.

* [geos](https://github.com/libgeos/geos): Geometry Engine, Open Source is a library for performing operations on two-dimensional vector geometries.

* [fiona](https://github.com/Toblerity/Fiona): reads and writes geographic data files and thereby helps Python programmers integrate geographic information systems with other computer systems.

* [shapely](https://github.com/Toblerity/Shapely): is a package for manipulation and analysis of planar geometric objects. 
## For raster data
* [rasterio](https://github.com/mapbox/rasterio):  reads and writes geospatial raster data.

## Vector and raster
* [gdal](https://github.com/OSGeo/gdal): Geospatial Data Abstraction Library is a translator library for raster and vector geospatial data formats.

* [earthPy](https://github.com/earthlab/earthpy): is a python package devoted to working with spatial and remote sensing data. EarthPy also contains an IO module that supports downloading data for the Earth Lab earth analytics courses and any user with a url and a zip file.

* [whiteBoxTools](https://github.com/giswqs/whitebox-python): can be used to perform common geographical information systems (GIS) analysis operations, remote sensing and image processing and many more.
## Machine learning libraries
* [eo-learn](https://github.com/sentinel-hub/eo-learn): makes extraction of valuable information from satellite imagery as easy as defining a sequence of operations to be performed on satellite imagery.

* [geospatial-learn](https://github.com/Ciaran1981/geospatial-learn):a Python lib for using scikit-learn, xgb and keras models with geo-spatial data. Some raster and vector manipulation is also included. 

* [scikit-image](https://github.com/scikit-image/scikit-image):  is a collection of algorithms for image processing.

* [scikit-learn](https://github.com/scikit-learn/scikit-learn): module for machine learning built on top of SciPy. 

## Download and process remote sensing data

* [getsentinel](https://bitbucket.org/wirrell/getsentinel/src/master/): a download, process, and masking tool for ESA Sentinel-X data.

* [Modis-Util](https://github.com/whistler/modis-util): a tool that makes it easy to search and download MODIS data on AWS.

* [pyModis](https://github.com/lucadelu/pyModis): library to download and process MODIS data from NASA server.

* [pySat](https://github.com/pysat/pysat): is a package providing a simple and flexible interface for downloading, loading, cleaning, managing, processing, and analyzing scientific measurements. 

* [rasterstats](https://github.com/perrygeo/python-rasterstats): is a module for summarizing geospatial raster datasets based on vector geometries.

* [sentinel2](https://github.com/csaybar/sentinel2): this a package for processing Sentinel-2 Level-1C product. 

* [sentinelhub](https://github.com/sentinel-hub/sentinelhub-py): allows users to make OGC (WMS and WCS) web requests to download and process satellite images within your Python scripts. It supports Sentinel-2 L1C and L2A, Sentinel-1, Landsat 8, MODIS and DEM.data source.

* [SatelliteImage](https://github.com/dgketchum/satellite_image): provides a class to process images from various satellites, return: geographic information, cloud mask, reflectance, brightness temperature.

* [sentinelpy](https://pypi.org/project/sentinelpy/): queries ESA Sentinel APIs for products.


* [stems](https://github.com/ceholden/stems): Spatio-temporal Tools for Earth Monitoring Science.
## Visualisation tools

* [folium](https://github.com/python-visualization/folium): makes it easy to visualize data that’s been manipulated in Python on an interactive Leaflet map.
  
* [descartes](https://pypi.org/project/descartes/): use geometric objects as matplotlib paths and patches.


* [matplotlib](https://github.com/matplotlib/matplotlib): is a comprehensive library for creating static, animated, and interactive visualizations in Python.