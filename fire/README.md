# EIS Fire Pilot Viz Notebooks

Demo notebooks from the EIS Fire pilot project. These are visualization notebooks developed by the Data Science Group (606.3) for the EIS Fire pilot project. These notebooks combine different visualization techniques such as time series visualizations and map visualizations to create dashboards which showcase a variety of remotely sensed observations. These notebooks were developed for use on EIS Fire's pilot project daskhub. They will not run without error if run on other instances which do not have access to the S3 buckets and on-disk datasets. Please contact 606.3 with questions about these notebooks. 

## Disclaimer

These notebooks are NOT actively supported. They are meant to be used as examples and for reference in creating interactive maps and time series visualization.

## Notebooks

### `SimpleVizDemo_1`

Description: Simple visualization notebook that reads in raster data on S3 buckets and produces interactive time series visualizations.

Memory Requirements: `8 GB`

### `EIS_Fire_Visualizations_Point_And_Click_Example_2`

Description: Dashboard notebook which renders time series of raster data where the geospatial location is selected by the user in the dashboard's map. Reads in data from S3 buckets and on-disk. Interactive.

Memory Requirements: `16 GB`

### `EIS_Fire_Visualizations_ShapeFile_Example_3`

Description: Dashboard notebook which clips and spatially averages time series of raster data to selected polygons selected by the user in the dashboard map window. Interactive. 
Memory Requirements: `16 GB`


### `EIS_Fire_Visualizations_Fire_Perims_Example_4`

Description: Dashboard notebook which clips and spatially averages time series of raster data to selected fire perimeter polygons selected by the user in the dashboard map window. Interactive. 

Memory Requirements: `16 GB`

### `EIS_Fire_Visualizations_WFS_Example_5`

Description: Dashboard notebook which lets user read in their own polygons by reading in an ESRI Web Feature Service (WFS) and spatially averages time series of raster data to WFS polygons selected by the user in the dashboard map window. Interactive.

Memory Requirements: `16 GB`

## Data

Data is pulling from S3 locations on EIS Fire AWS instances and some hard disk datasets on EIS Fire EFS space. These notebooks will not run as is without the notebooks being run on EIS Fire's daskhub.

S3 Bucket: `s3://dh-eis-fire-usw2-shared`
Hard disk: `/home/jovyan/efs/eis-fire-tropomi`

## Python Ecosystem
The visualization backend used is all within the `Holoviews` family of notebook-friendly visualization python packages. The packages are listed below:
- `holoviews`
- `hvplot`
- `geoviews`
- `panel`

## Notebook requirements
Jupyterlab Extension: `@pyviz/jupyterlab_pyviz`

