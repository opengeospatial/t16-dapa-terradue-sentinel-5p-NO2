## OGC Testbed 16 - Terradue DAPA demonstrator

This demonstrator uses Sentinel-5P tropospheric NO2 column density to show-case the DAPA API approach for gridded data and supports the DAPA API evaluation by several data scientists or earth scientists regarding:

- Learning curve to use the API

- Richness of accessible functionality

- Amount of code needed to execute some common analyses

The typical user stories under evaluation are:

* _As a data scientist, I want to access geospatial data for a specific area in a simple function call_

* _As a data scientist, I want to retrieve data for a single point in time or as an average value over a time period._

* _As a data scientist, I want to retrieve a single value that averages all data in the target geometry for each time step._

* _As a data scientist, I want to retrieve the full time series for each data point._ 

* _As a data scientist, I want to  calculate the minimum, maximum, and average values for any given data retrieval subset_

The outcome of the evaluation will allow the API developers and endpoint providers to further refine the DAPA API and increase ease of use based on the feedback provided by the scientists.

### About the Sentinel-5P tropospheric NO2 column density dataset 

This demonstrator uses data from the Copernicus Sentinel-5P satellite and exposes the monthly (from May 2018 to April 2020) averaged nitrogen dioxide concentrations over a portion of Europe. 
Concentrations of short-lived pollutants, such as nitrogen dioxide, are indicators of changes in economic slowdowns and are comparable to changes in emissions.

### Run the demonstrator on Binder

Binder will launch an instance with all the resources needed to get started with DAPA and the Sentinel-5P NO2 tropospheric column density dataset over Europe.

These resources are: 

- the DAPA documentation (landing page)
- the DAPA Open API documentation
- a JupyterLab instance filled with examples using the DAPA API
- the Sentinel-5P NO2 tropospheric column density data consumed by the DAPA API

Click on the badge below to start your own DAPA demonstator instance:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/opengeospatial/t16-dapa-terradue-sentinel-5p-NO2/master?urlpath=/proxy/8001/)

