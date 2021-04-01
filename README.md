# Open Science Education

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/ESIPFed/open-data-education/master?urlpath=lab)
[![Build Status](https://travis-ci.org/dask/dask-examples.svg?branch=master)](https://travis-ci.org/ESIPFed/open-data-education)

## Introduction

The goal of this tutorial is to introduce users to working with NASA satellite imagery and utilizing Amazon Web Services' Open Data program. Through a series of modules, the user will develop an end-to-end workflow for working with satellite imagery, learn about geoscientific Python tools, and utilize a parallel computation platform on the cloud (i.e. the Pangeo Platform). 

## Description

The contents of this repository (Jupyter Notebooks) is meant to be executed through a web browser. 

`Introduction to Basic Python` is a notebook that describes open source Python packages that have been developed to seamlessly read and process spatio-temporal satellite imagery like Landsat or Sentinel.

The `Introduction to Cloud Computing` is a notebook goes into basics of cloud computing for satellite imagery and procesing. It is written for entry-level folks, and lacks full-depth walk-through.

The `Using Dask to process imagery to calculate NDVI via DASK` is a notebook which integrates all the previous tutorials. The notebook sifts through all the Landsat scenes for Amazonia (since 2013), and calculates NDVI for each scene. Dask is utilized to do parallelization.

## Installation notes

**Follow the workshop with just your browser?**   
You can use the "launch binder" link above at the top of this README, which will launch a notebook instance on Binder with all required libraries installed.

:

```

```


## Downloading the tutorial materials

**Note**: *This repository is actively being developed as a tutorial, so we will be updating the materials without notifications. To update your local copy, you can download the latest version again, or do a `git pull` if you are using git.*

If you have git installed, you can always get the tutorial materials by cloning this repo:

```
git clone https://github.com/ESIPFed/open-data-education.git
```

Also, you can download the repository as a .zip file by heading over to the GitHub repository (https://github.com/ESIPFed/open-data-education.git) in
your browser and click the green "Download" button in the upper right:


## Running the tutorial 

**Note**: *As it is to be run on public infrastructure, you can use Binder script at the root folder.*

## Tutorial index 

|Name |Description|link|
|-----|-----------|----|
|Introduction to Cloud|Details on cloud technologies       |[Tutorial 1](/intotocloud.ipynb)  |
|Open datasets  |Publically availiable datasets     | [Tutorial 2](/Opendatasets.ipynb)  |
|Xarray |Introduction to Xarray    | [Tutorial 3](/x-array.ipynb)  |
|Dask |Introduction to Dask    | [Tutorial 4](/Dask.ipynb)  |
|Visualization |Introduction to HoloViews    | [Tutorial 5](/Visualize.ipynb)  |
|Scaling-up |Using Dask to process imagery to calculate NDVI via DASK    | [Tutorial 6](/Scale-up.ipynb)  |

## Issues

**Feedback/new tutotrial**   
You can request new content or give general feedback through Gitub issues as well. Additionally, feel free to send us a pull request.

**Notebook related**   
You can log issues using the GitHub ticketing, and we will address it at our earliest

## Authors

Aji John and Amanda Tan at University of Washington .
