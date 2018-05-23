---
layout: page
title: Basic Mapping
tags: [QGIS, GIS, spatial data, mapping, vector data, raster data, graphics]
date: 2018-05-23
comments: false
---

## Introduction
Maps allows us to display information about sampling locations and experimental design. Often times, maps are overcrowded, the fonts are too small, or the symbols are difficult to differentiate between. Creating a map that is easily understood is essential for others to understand our research. QGIS is my go-to mapping program because it's available for most operating systems, it's open-source,and it's easy to manipulate the maps you create. With just a few clicks, you'll have a simple, beautiful map that displays your data in a graphically pleasing way. Popular, alternative tools for mapping include the package ggplot2 in R, ArcGIS, and Surfer.

---

## Terminology
- Spatial data: the geographic location of features and boundaries
- Vector data: a type of spatial data that uses vertices and paths; this type of data is useful for features that are not changing such as topology
- Vector points: XY coordinates, usually a latitude and a longitude
- Vector lines: represent linear features such as roads and rivers; they are constructed by connecting points with paths
- Vector polygons: show boundaries and are constructed when a  set of points connected with paths is closed
- Raster data: a type of spatial data that uses pixels; this type of data is useful for features that frequently change such as rainfall and temperature
- Attribute data: descriptive data of geographic features; examples - site type, site name, and depth
- Shapefile: file format that allows you to store the location and attribute information of geographic features
- Symbology: a layer's visual appearance on a map

---

## Getting Setup
[![](assets/img/resized_qgis_logo.png)](https://qgis.org/en/site/)

Click on the logo above to go to the QGIS website where you can download the software.

Download the files used in this guide [here](https://drive.google.com/open?id=1bx_W0hNEfw537NfltsHiskRJlAfgNZz4)

Additional files for mapping can be downloaded from [the natural earth](https://www.naturalearthdata.com/).

---

## Making a Map
