# EIS Hydro Pilot Viz Notebooks

Demo notebooks from the EIS Hydro pilot project. These are visualization notebooks developed by the Data Science Group (606.3) for the EIS Hydro pilot project. These notebooks combine different visualization techniques such as time series visualizations and map visualizations to create dashboards which showcase a variety of remotely sensed observations. These notebooks were developed for use on EIS Hydro's pilot project daskhub. They will not run without error if run on other instances which do not have access to the S3 buckets and on-disk datasets. Please contact 606.3 with questions about these notebooks. 

## Disclaimer

These notebooks are NOT actively supported. They are meant to be used as examples and for reference in creating interactive maps and time series visualization.

## snowex-demo

This repository contains tutorial notebook prepared for SnowEx Workshop 2021.  The tutorial is for interacting with LIS model output, including, understand the structure of LIS model output (netCDF files); open, interact, and visualize LIS output; and compare LIS simulations to raster and point datasets collected during the 2017 SnowEx field campaign in Colorado.

## ilab eis workflows

This repository contains files related to the Mississippi River Delta case study of the Earth Information System - Freshwater pilot project.
NOTE: This repository is no longer maintained. See https://git.mysmce.com/eis-freshwater/eis-freshwater-case-studies for the latest version.

## Python Ecosystem

The visualization backend used is all within the `Holoviews` family of notebook-friendly visualization python packages. The packages are listed below:

- `holoviews`
- `hvplot`
- `geoviews`
- `panel`

## Notebook requirements

Jupyterlab Extension: `@pyviz/jupyterlab_pyviz`
