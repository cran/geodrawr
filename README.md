
<!-- README.md is generated from README.Rmd. Please edit that file -->

# geodrawr

An interactive tool for making geo-spatial objects by clicks on the map

## Installation

You can install the released version from [GitHub](https://github.com/)
with:

``` r
# install.packages("devtools")
devtools::install_github("Curycu/geodrawr")
```

## How to Use?

There are three draw tools :

``` r
library(geodrawr)

# draw_polygons()
# draw_lines()
# draw_points()
```

#### case polygons

![draw\_polygons](draw_polygons.gif)

  - click the map to make edges  
  - push **Make** button to make a polygon from the edges  
  - push **Save** button to save polygons as rds file  
  - push **Load** button to load polygons from rds file

#### case lines

![draw\_lines](draw_lines.gif)

  - click the map to make edges  
  - push **Make** button to make a line from the edges  
  - push **Save** button to save lines as rds file  
  - push **Load** button to load lines from rds file

#### case points

![draw\_points](draw_points.gif)

  - click the map to make a point  
  - push **Save** button to save points on the map as a rds file  
  - push **Load** button to load points from rds file
