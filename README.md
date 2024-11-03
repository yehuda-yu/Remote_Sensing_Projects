# Remote Sensing Projects

## Overview
This repository contains a collection of Python notebooks for remote sensing applications, focusing on vegetation, soil, and atmospheric analysis. The projects utilize Python and Google Earth Engine (GEE) for processing and analyzing remote sensing data.

## Contents

### Energy and Radiation
- `Energy_Balance.ipynb`: Implementation of energy balance calculations using gee data. 
- `remoreSensing_Shortwave_rad.ipynb`: Processing and analysis of shortwave radiation data
- `Trapezoid_method.ipynb`: Implementation of the trapezoid method for soil moisture estimation

### Vegetation and Productivity
- `Montein_GPP.ipynb`: Gross Primary Production (GPP) calculations using the Monteith approach
- `RS_FAO.ipynb`: Remote sensing applications following FAO (Food and Agriculture Organization) guidelines

### Water and Evapotranspiration
- `evapotranspiration_fao.ipynb`: FAO-based evapotranspiration calculations
- `RADAR.ipynb`: RADAR data processing and analysis for moisture detection

### Data Processing
- `read_netcdf_image_as_data_cube.ipynb`: Tools for handling NetCDF files as data cubes

## Dependencies
- Python
- Google Earth Engine Python API
- Jupyter Notebook
- Common scientific Python libraries:
  - NumPy
  - Pandas
  - xarray (for NetCDF handling)
  - matplotlib
  - earthengine-api
  - caropy
  - rasterio

## Usage
1. Ensure you have all dependencies installed
2. Open the desired notebook using Jupyter Notebook or Colab
3. Follow the instructions within each notebook for specific applications

## Project Structure
```
Remote_Sensing_Projects/
├── Energy_Balance.ipynb
├── Montein_GPP.ipynb
├── RADAR.ipynb
├── RS_FAO.ipynb
├── Trapezoid_method.ipynb
├── evapotranspiration_fao.ipynb
├── read_netcdf_image_as_data_cube.ipynb
└── remoreSensing_Shortwave_rad.ipynb
```

## Features
- Energy balance calculations for land surface
- Vegetation productivity analysis
- Soil moisture estimation
- Evapotranspiration modeling
- RADAR data processing
- NetCDF data handling
- Integration with Google Earth Engine

## License
This project is licensed under the HUJI License.

## Author
Yehuda Yungstein (Supervised by Dr. David Helman)

## Acknowledgments
This repository was created as part of a Remote Sensing course and incorporates standard methodologies from the field of remote sensing and Earth observation.
