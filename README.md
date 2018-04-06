# NetCDF WINGS Component

This repository contains a Jupyter Notebook that describes the needed steps to create a workflow to open and manipulate NetCDF files in [WINGS](http://www.wings-workflows.org).

Inputs Files:
1. netCDF files containing ECMWF reanalysis data for the months of October, November, and December 2010:  
- Oct2010.nc
- Nov2010.nc
- Dec2010.nc
2. Text files containing information about the needed variables and units from the connecting model. In this example, the model is assumed to be [TOPOFLOW](https://github.com/peckhams/topoflow):  
- modelVar.txt
- modelVarUnits.txt

Output files:
1. Pickled files to link the various components
- pickle1.p
- pickle2.p
- pickle3.p
- pickle4.p
- pickle5.p
- pickle6.p
2. A warning file output by the workflow to signal that some variables are missing from the data file.
3. The binary files needed by TOPOFLOW named according to the variable they contain:
- Albedo.txt
- Forecast surface roughness.txt
- Precipitation rate.txt  
- Relative Humidity.txt  
- Skin Temperature.txt  
- Surface Pressure.txt  
- Total cloud cover.txt  
- Wind reference height.txt
- Wind Speed.txt
