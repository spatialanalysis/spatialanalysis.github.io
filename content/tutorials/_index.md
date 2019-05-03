---
title: "Tutorials"
description: "Find learning resources and tutorials for open source spatial analysis"
draft: false
layout: subsection
slug: tutorials
---

Note: tutorials are currently still under development, and more will be added in the upcoming year. All tutorials are in the R programming language, save for one PostGIS tutorial.

## R Spatial Workshop Notes - **new!**

Workshop notes and scripts from the R Spatial Workshop can be found at the [**following link**](https://spatialanalysis.github.io/workshop-notes/). Topics to be covered include spatial data manipulation, mapping, and interactive visualization. 

Please see our [Events](https://spatialanalysis.github.io/events/) page for more information about these workshops.

## Mapping Array of Things Data With Spatial Statistics - **new!**

This two-part [spatial statistics tutorial](https://geodacenter.github.io/aot-workshop/) was put together by Anais Ladoy, Isaac Kamber, Marynia Kolak, Julia Koschinsky, and Luc Anselin, and focuses on using [**Array of Things sensor data**](https://aot-file-browser.plenar.io/data-sets/chicago-complete) to create map visualizations and perform spatial analysis. It has been taught at Argonne National Laboratory in August 2018 and at the Chicago Department of Public Health in April 2019.

Download data for this workshop at [**this Github link**](https://github.com/GeoDaCenter/aot-workshop/tree/master/Data).

* [**Part 1: Sensor Data Access and Mapping Basics**](https://geodacenter.github.io/aot-workshop/Part1-AOT.html): Learn to read and inspect data, convert data to spatial formats, map nodes with community areas, and develop a density map of sensors using buffers and re-projected data.
* [**Part 2: Interpolating Temperature Data**](https://geodacenter.github.io/aot-workshop/Part2-AOT.html): Interpolate temperature readings to develop a kriging surface. Learn some filtering and aggregation techniques for data wrangling practice, and then prepare for two models of kriging (spherical and exponential). 

![Array of Things Leaflet Interactive Maps with Kriging](/tutorials/_index_files/AOT Graphic.jpg)

## Introduction to Spatial Data Science

Below are the R lab notes from Luc Anselin's [Introduction to Spatial Data Science](https://spatial.uchicago.edu/content/lectures-luc-anselin-uchicago) course at the University of Chicago taught in Fall 2018. These labs mirror the [GeoDa notebooks](http://geodacenter.github.io/documentation.html), but use R rather than GeoDa. Thank you Grant Morrison for his work on these R tutorials.

* [**Spatial Data Handling**](https://spatialanalysis.github.io/lab_tutorials/1_R_Spatial_Data_Handling.html): Import, manipulate, and map abandoned vehicle data to make a choropleth map of abandoned vehicles per capita for Chicago community areas.
* [**Exploratory Data Analysis 1 - Univariate and Bivariate Analysis**](https://spatialanalysis.github.io/lab_tutorials/2_R_EDA_1.html): Explore NYC socioeconomic data by borough and perform exploratory spatial analysis involving univariate plots, smoothing methods, and linear fits.
* [**Exploratory Data Analysis 2 - Multivariate Exploration**](https://spatialanalysis.github.io/lab_tutorials/3_R_EDA_2.html): Continue to explore NYC socioeconomic data using spatial data analysis methods for three or more variables, including scatter plots, bubble plots, and parallel coordinate plots.
* [**Basic Mapping**](https://spatialanalysis.github.io/lab_tutorials/4_R_Mapping.html): Finish working with NYC socioeconomic data by creating and customizing a variety of maps, including choropleth maps, conditional maps, and cartograms.

![Choropleth Map of Abandoned Vehicle Per Capita in Chicago and Box Map of Rent in NYC](tutorials/choropleth-and-box-map.png)

## Cluster Analysis in R

The following tutorials were prepared by Luc Anselin in 2017 for his Introduction to Spatial Data class. 

* [**Dimension Reduction Methods**](https://geodacenter.github.io/tutorials/pca_mds/pca_mds.html): Learn about Principal Components Analysis (PCA) and multidimensional scaling using the [Guerry_85]() dataset and the `foreign` and `ggplot2` R packages.
* [**Classic Clustering Methods**](https://geodacenter.github.io/tutorials/classic_cluster/classic_cluster.html): Use hierarchical clustering and k-means clustering on the same dataset with the `hclust` and `kmeans` functions in base R.
* [**Spatially Constrained Clustering Mehods**](https://geodacenter.github.io/tutorials/spatial_cluster/skater.html): Carry out contiguity-constrained clustering with SKATER algorithm and the `rgdal`, `spdep`, and `maptools` packages.

## Basic R Tutorials

The following are notes that Luc Anselin has put together to introduce R to his undergraduate classes. They provide an overview of data manipulation and visualization methods, using geographic data as an example.

* [**Manipulating Data Frames**](html/dataframes-notebook.html): Read, write, summarize, and wrangle data with the `foreign` R package (for dbf files) and the `tidyverse`.
* [**Data Visualization (1)**](html/graphs1-notebook.html): Visualize data using the `ggplot2` package, creating scatterplots and fitting lines to NYC sub-borough data.
* [**Data Visualization (2)**](html/graphs2-notebook.html): Extend the visualizations of the previous tutorial, using `ggplot2` to customize scatterplots, create histograms, boxplots, and more. Learn about reshaping data into a tidy format using `tidyr`.
* [**Basic Mapping**](html/basic-mapping-notebook.html): Manipulate and map spatial data, creating custom choropleth maps with NYC borough data, using the `sf`, `tmap`, and `RColorBrewer` packages.

## Spatial Join in R

[**This tutorial**](https://makosak.github.io/SpatialDataScience-Notebooks/SpatialJoin.html), put together by Marynia Kolak in November 2017, shows how to do spatial joins and aggregations using the `spatialeco`, `foreign`, and `rgdal` packages. Updated content using the `sf` package will be uploaded shortly. 

## PostGIS Tutorial

Learn how to create spatial queries and perform spatial analysis in PostGIS databases using [**this tutorial**](https://github.com/Coleridge-Initiative/ada-2017-welfare/blob/master/notebooks/spatial_notebooks/Spatial-Queries-in-PostGIS.ipynb) developed by Clayton Hunter and Julia Koschinsky.
