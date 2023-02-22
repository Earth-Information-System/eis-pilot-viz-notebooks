# EIS Pilot Viz Notebooks

Demo notebooks from the EIS pilot project. These are visualization notebooks developed by the Data Science Group (606.3) for the EIS pilot project. These notebooks combine different visualization techniques such as time series visualizations and map visualizations to create dashboards which showcase a variety of remotely sensed observations. These notebooks were developed for use on EIS Fire's project daskhubs. They will not run without error if run on other instances which do not have access to the S3 buckets and on-disk datasets. Please contact 606.3 with questions about functionality of these notebooks. 

## Disclaimer

These notebooks are NOT actively supported. They are meant to be used as examples and for reference in creating interactive maps and time series visualization.

## Python Ecosystem

The visualization backend used is all within the `Holoviews` family of notebook-friendly visualization python packages. The packages are listed below:

- `holoviews`
- `hvplot`
- `geoviews`
- `panel`

## Notebook requirements

Jupyterlab Extension: `@pyviz/jupyterlab_pyviz`

