# Toolbox for Vegetation Indices and Biophysical Parameters.

## This is the reporitory of Jupyter Notebooks for the development of low-level Vegetation Indices and Biophysical Parameters. 
These datasets are not longer maintained in the context of the CLMS Vegetation Phenology and Productivity (HR-VPP) therefore this repository aims to provide the tools needed to calculate these variables independently using Sentinel-2 data. 


* [Leaf Area Index (LAI)](https://github.com/copernicus-land/HRVPP-VIs/blob/main/openEO_notebooks/LAI.ipynb).
  The Leaf Area Index (LAI) is defined as half the total area of a canopy's green elements per unit of horizontal ground area. The satellite-derived value corresponds to the total green LAI of all the canopy layers,   including the understory, which may represent a significant contribution, particularly for forests. It is recognized as an Essential Climate Variable (ECV) by the Global Climate Observing System (GCOS) and is        widely used in climate monitoring, ecosystem assessment, and land surface modelling.
  
* [Fraction of Absorbed Photosynthetically Active Radiation (fAPAR)](https://github.com/copernicus-land/HRVPP-VIs/blob/main/openEO_notebooks/FAPAR.ipynb).
  Fraction of Absorbed Photosynthetically Active Radiation (FAPAR) a key biophysical variable describing the fraction of incoming solar radiation absorbed by green and living vegetation elements for photosynthesis.    It is recognized as an Essential Climate Variable (ECV) by the Global Climate Observing System (GCOS) and is widely used in climate monitoring, ecosystem assessment, and land surface modelling.

* [Normalized Difference Vegetation Index (NDVI) ](http://github.com/copernicus-land/HRVPP-VIs/blob/main/openEO_notebooks/NDVI.ipynb).
  The Normalised Difference Vegetation Index (NDVI) is a proxy to quantify the vegetation amount. It is defined as NDVI=(NIR-Red)/(NIR+Red) where NIR corresponds to the reflectance in the near infrared band, and Red   to the reflectance in the red band.
  
* [Plant Phenology Index (PPI) ](https://github.com/copernicus-land/HRVPP-VIs/blob/main/openEO_notebooks/PPI.ipynb).
  The Plant Phenology Index (PPI) is a satellite-based vegetation index designed to monitor vegetation growth cycles (phenology) with improved sensitivity during early spring green-up and late autumn senescence.       Unlike traditional indices like NDVI, PPI maintains a linear relationship with green leaf area index (LAI) across the entire growing season.
