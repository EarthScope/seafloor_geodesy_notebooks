# Seafloor Geodesy Notebooks

This repository contains Jupyter notebooks for running GNSS-A processing in the EarthScope GeoLab environment, using the [`es_sfgtools`](https://github.com/EarthScope/es_sfgtools) library.

## Overview

These notebooks provide a complete workflow for processing seafloor geodesy data, including:
- Data retrieval and preparation
- Survey metadata generation and refinement
- GNSS-A positioning analysis using GARPOS
- Visualization and quality control

## Requirements

- An Earthscope account - https://www.earthscope.org/
- Access to EarthScope GeoLab. Please contact one of the maintainers if you need access. 

## Getting Started

### Launch in GeoLab

Click the button below to launch these notebooks in EarthScope GeoLab:

[![Launch in GeoLab](https://img.shields.io/badge/Launch-GeoLab-blue?style=for-the-badge)](https://geolab.earthscope.cloud/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FEarthScope%2Fseafloor_geodesy_notebooks.git&urlpath=lab%2Ftree%2Fseafloor_geodesy_notebooks.git%2Fnotebooks%2F&branch=main)

When prompted, select **"Other"** and paste the latest Docker image:

`public.ecr.aws/earthscope/sfg-geolab:latest`

### Available Docker Images

All available images and tags can be found in the [EarthScope ECR Gallery](https://gallery.ecr.aws/earthscope/sfg-geolab).

## Repository Structure

seafloor_geodesy_notebooks/
    notebooks/ # Jupyter notebooks for GNSS-A processing
    README.md

## Notebooks

| Notebook | Description |
|----------|-------------|
| `run_garpos.ipynb` | Test data retrieval and processing pipelines |
| `station_metadata_generator.ipynb` | Generate and update station metadata files |
| `refine_survey_metadata.ipynb` | Refine survey metadata and visualize survey paths |


**Maintainers**: Mike Gottlieb, Franklyn Dunbar, Rachel Akie

**Organization**: [EarthScope](https://www.earthscope.org/)

*Last updated: December 2025*