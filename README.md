# scanpy squidpy demo 2021

Welcome to the scanpy and squidpy demo session in July 2021. This repository contains all necessary information for the hands-on practices to start with scanpy and squidpy.

## Prerequisites

All demo session notebooks are designed to work out of the box in Google Colabs and are equipped with the respecetive installation commands for scanpy and squidpy. However, to explore the full functionality of both scanpy and squidpy, we recommend to install both tools locally. 

### scanpy installation

We provide several ways to work with scanpy: a Docker environment, an installation manual via `yaml` file and Google Colabs.

A docker container comes with a working R and Python environment, and is now available [here](https://hub.docker.com/r/leanderd/single-cell-analysis) thanks to [Leander Dony](https://github.com/le-ander). Please note that the docker container does not contain the squidpy package.

The manual installation using a `yaml` file can be found the [single-cell tutorial page](https://github.com/theislab/single-cell-tutorial#environment-set-up). Please note that the single-cell tutorial uses both R and Python and calls R via the rpy2 package, where we experienced that it might be troublesome to set up, especially on Windows machines.  

All notebooks in this demo session are equipped with the installation commands for Google Colabs, so please skip those when working on your local environment.

## squidpy installation

You can install squidpy via PyPi using

```
pip install squidpy
```
or with napari included
```
pip install 'squidpy[interactive]'
```

## Demo session schedule

The demo session on scanpy and squidpy encompasses 
* an introduction to single-cell RNA-sequencing data analysis 
* the basic functionality of scanpy and anndata
* batch effect correction methods (scIB)
* scanpy extensions for RNA velocity (scVelo)
* spatial data analysis using squidpy  
