# EIS SeaLevel Pilot Viz Notebooks

Demo notebooks from the EIS Sealevel pilot project. These are visualization notebooks developed by the Data Science Group (606.3) for the EIS Fire pilot project. These notebooks combine different visualization techniques such as time series visualizations and map visualizations to create dashboards which showcase a variety of remotely sensed observations. These notebooks were developed for use on EIS Sealevel's pilot project daskhub. They will not run without error if run on other instances which do not have access to the S3 buckets and on-disk datasets. Please contact 606.3 with questions about these notebooks.

## Disclaimer

These notebooks are NOT actively supported. They are meant to be used as examples and for reference in creating interactive maps and time series visualization.

## cryosphere model comparison tool


The Cryospheric Model Comparison Tool (CmCt) is designed to facilitate rapid comparison between ice sheet model results, and between ice sheet models and available observations from Greenland. Currently, the CmCt is used to compare ice sheet models provided by the user with remotely sensed satellite ICESat (Ice, Cloud, and land Elevation Satellite) laser altimetry, ERS-1, ERS-2 (European Remote-Sensing Satellite), and Envisat (Environmental Satellite) radar altimetry data.

## Python Ecosystem

The visualization backend used is all within the `Holoviews` family of notebook-friendly visualization python packages. The packages are listed below:

- `holoviews`
- `hvplot`
- `geoviews`
- `panel`

## Notebook requirements

Jupyterlab Extension: `@pyviz/jupyterlab_pyviz`
