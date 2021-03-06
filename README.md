
# workshop-scripts

This repository contains scripts from the each quarter of the [R Spatial
Workshop](https://spatialanalysis.github.io/events/) run at the Center
for Spatial Data Science at the University of Chicago.

Workshops are run by Angela Li, R Spatial Advocate, and detailed notes
for the workshops can be found
[online](https://spatialanalysis.github.io/workshop-notes/).

Each quarter’s contents can be found in a separate folder in each topic
repository with that quarter’s name, ie
`gis-visualization/winter-2019`.

## Fall 2019

### Introduction to Spatial Data Science

| Date       | Topic                                                                                                                            | R Script / R Markdown                                                           |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| 2019-10-08 | [Spatial data handling](https://spatialanalysis.github.io/workshop-notes/spatial-data-handling.html)                             | [01-spatial-data-handling.R](intro-spatial-data-sci/01-spatial-data-handling.R) |
| 2019-10-15 | [Spatial data handling pt. 2](https://spatialanalysis.github.io/workshop-notes/spatial-data-handling.html)                       | [week2-fall2019-workshop.R](intro-spatial-data-sci/week2-fall2019-workshop.R)   |
| 2019-10-22 | [Basic mapping pt. 1](https://spatialanalysis.github.io/workshop-notes/basic-mapping.html)                                       | [week3-fall2019-workshop.R](intro-spatial-data-sci/week3-fall2019-workshop.R)   |
| 2019-10-29 | [Basic mapping pt. 2](https://spatialanalysis.github.io/workshop-notes/basic-mapping.html)                                       | [week4-fall2019-workshop.R](intro-spatial-data-sci/week4-fall2019-workshop.R)   |
| 2019-11-05 | [Contiguity weights](https://spatialanalysis.github.io/workshop-notes/spatial-autocorrelation.html)                              | [week5-fall2019-workshop.R](intro-spatial-data-sci/week5-fall2019-workshop.R)   |
| 2019-11-12 | [Distance-based weights](https://spatialanalysis.github.io/workshop-notes/spatial-autocorrelation.html)                          | [week6-fall2019-workshop.R](intro-spatial-data-sci/week6-fall2019-workshop.R)   |
| 2019-11-19 | [Spatial autocorrelation with rgeoda](https://spatialanalysis.github.io/workshop-notes/spatial-autocorrelation-with-rgeoda.html) | [intro-rgeoda.Rmd](intro-spatial-data-sci/intro-rgeoda.Rmd)                     |
| 2019-11-26 | Spatial clustering with rgeoda                                                                                                   |                                                                                 |

## Spring 2019

### GIS and Visualization

| Date       | Topic                                                                                                                                                        | R Script / R Markdown                                                              |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| 2019-04-10 | [Introduction to spatial data](https://spatialanalysis.github.io/workshop-notes/introduction-to-spatial-data.html)                                           | [import-data.R](gis-visualization/spring-2019/R/import-data.R)                     |
| 2019-04-17 | [Single-dataset GIS operations](https://spatialanalysis.github.io/workshop-notes/single-dataset-gis-operations.html)                                         | [gis-learning.R](gis-visualization/spring-2019/R/gis-learning.R)                   |
| 2019-04-24 | [Multi-dataset GIS operations](https://spatialanalysis.github.io/workshop-notes/multiple-dataset-gis-operations-visualization.html)                          | [gis-learning-2.R](gis-visualization/spring-2019/R/gis-learning-2.R)               |
| 2019-05-01 | [Multi-dataset GIS operations pt. 2: spatial join](https://spatialanalysis.github.io/workshop-notes/multiple-dataset-gis-operations-visualization-pt-2.html) | [spatial-join.R](gis-visualization/spring-2019/R/spatial-join.R)                   |
| 2019-05-08 | No workshop                                                                                                                                                  |                                                                                    |
| 2019-05-15 | [Working with R Markdown](https://spatialanalysis.github.io/workshop-notes/r-markdown-and-custom-maps.html)                                                  | [rmarkdown-practice.Rmd](gis-visualization/spring-2019/doc/rmarkdown-practice.Rmd) |
| 2019-05-22 | [Custom maps with tmap](https://spatialanalysis.github.io/workshop-notes/custom-and-animated-maps.html)                                                      | [custom-map.Rmd](gis-visualization/spring-2019/doc/custom-map.Rmd)                 |
| 2019-05-29 | [Interactive map packages](https://spatialanalysis.github.io/workshop-notes/interactive-maps.html)                                                           | [interactive-maps.Rmd](gis-visualization/spring-2019/doc/interactive-maps.Rmd)     |

### Raster Data and Kriging

| Date       | Topic                                                                                                                                                                                                                                              | R Script / R Markdown                                                                                                                       |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| 2019-04-10 | [Introduction to raster data](https://datacarpentry.org/r-raster-vector-geospatial/01-raster-structure/index.html)                                                                                                                                 | [raster-intro.R](raster-kriging/spring-2019/R/raster-intro.R)                                                                               |
| 2019-04-17 | [Plotting raster data](https://datacarpentry.org/r-raster-vector-geospatial/02-raster-plot/index.html)                                                                                                                                             | [raster-plotting.R](raster-kriging/spring-2019/R/raster-plotting.R)                                                                         |
| 2019-04-24 | [Projecting raster data](https://datacarpentry.org/r-raster-vector-geospatial/03-raster-reproject-in-r/index.html)                                                                                                                                 | [raster-projection.R](raster-kriging/spring-2019/R/raster-projection.R)                                                                     |
| 2019-05-01 | [Multiband raster data](https://datacarpentry.org/r-raster-vector-geospatial/05-raster-multi-band-in-r/index.html), [cropping raster to vector data](https://datacarpentry.org/r-raster-vector-geospatial/11-vector-raster-integration/index.html) | [raster-multiband.R](raster-kriging/spring-2019/R/raster-multiband.R)                                                                       |
| 2019-05-08 | No workshop                                                                                                                                                                                                                                        |                                                                                                                                             |
| 2019-05-15 | [Interpolation, pt. 1](https://spatialanalysis.github.io/workshop-notes/introduction-to-interpolation.html)                                                                                                                                        | [interpolation-meuse.R](https://github.com/spatialanalysis/workshop-scripts/blob/master/raster-kriging/spring-2019/R/interpolation-meuse.R) |
| 2019-05-22 | [Interpolation, pt. 2](https://spatialanalysis.github.io/workshop-notes/interpolation-with-array-of-things-data.html)                                                                                                                              | [interpolation-aot.R](https://github.com/spatialanalysis/workshop-scripts/blob/master/raster-kriging/spring-2019/R/interpolation-aot.R)     |

## Winter 2019

### GIS and Visualization

| Date       | Topic                                                                                                                                         | R Script / R Markdown                                                                |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| 2019-01-15 | [Introduction to spatial data](https://spatialanalysis.github.io/workshop-notes/introduction-to-spatial-data.html)                            | [01-intro.R](gis-visualization/winter-2019/R/01-intro.R)                             |
| 2019-01-22 | [Single-dataset GIS operations](https://spatialanalysis.github.io/workshop-notes/single-dataset-gis-operations.html)                          | [02-gis-1.R](gis-visualization/winter-2019/R/02-gis-1.R)                             |
| 2019-01-29 | [Multi-dataset GIS operations pt 1](https://spatialanalysis.github.io/workshop-notes/multiple-dataset-gis-operations-visualization.html)      | [03-gis-2.R](gis-visualization/winter-2019/R/03-gis-2.R)                             |
| 2019-02-05 | [Multi-dataset GIS operations pt 2](https://spatialanalysis.github.io/workshop-notes/multiple-dataset-gis-operations-visualization-pt-2.html) | [04-gis-3.R](gis-visualization/winter-2019/R/04-gis-3.R)                             |
| 2019-02-12 | [R Markdown](https://spatialanalysis.github.io/workshop-notes/r-markdown-and-custom-maps.html)                                                | [05-rmarkdown.Rmd](gis-visualization/winter-2019/doc/05-rmarkdown.Rmd)               |
| 2019-02-19 | [Custom static maps and animated maps](https://spatialanalysis.github.io/workshop-notes/custom-and-animated-maps.html)                        | [06-custom-maps.Rmd](gis-visualization/winter-2019/doc/06-custom-maps.Rmd)           |
| 2019-02-26 | [Interactive maps](https://spatialanalysis.github.io/workshop-notes/interactive-maps.html)                                                    | [07-interactive-maps.Rmd](gis-visualization/winter-2019/doc/07-interactive-maps.Rmd) |
| 2019-02-26 | [Interactive maps with Shiny](https://spatialanalysis.github.io/workshop-notes/interactive-maps-with-shiny.html)                              | [app.R](gis-visualization/winter-2019/R/leaflet-example/app.R)                       |
