- [Earth-Observation-Libraries](#earth-observation-libraries)
  - [General data analysis tools](#general-data-analysis-tools)
  - [For vector data](#for-vector-data)
  - [For raster data](#for-raster-data)
  - [Vector and raster](#vector-and-raster)
  - [Machine learning libraries](#machine-learning-libraries)
  - [Download and process remote sensing data](#download-and-process-remote-sensing-data)
  - [Visualisation tools](#visualisation-tools)

# Earth-Observation-Libraries
Below is an attempt to document and list the most common;y used python libraries, used for Earth Observation data analysis. This list is a live document and it will be updated ofter. 

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