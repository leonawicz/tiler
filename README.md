
<!-- README.md is generated from README.Rmd. Please edit that file -->
tiler <a hef="https://github.com/leonawicz/tiler/blob/master/data-raw/tiler.png?raw=true" _target="blank"><img src="https://github.com/leonawicz/tiler/blob/master/inst/tiler.png?raw=true" style="margin-left:10px;margin-bottom:5px;" width="120" align="right"></a>
======================================================================================================================================================================================================================================================================

[![CRAN status](http://www.r-pkg.org/badges/version/tiler)](https://cran.r-project.org/package=tiler) [![CRAN downloads](http://cranlogs.r-pkg.org/badges/grand-total/tiler)](https://cran.r-project.org/package=tiler) [![Rdoc](http://www.rdocumentation.org/badges/version/tiler)](http://www.rdocumentation.org/packages/tiler) [![Travis-CI Build Status](https://travis-ci.org/leonawicz/tiler.svg?branch=master)](https://travis-ci.org/leonawicz/tiler) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/leonawicz/tiler?branch=master&svg=true)](https://ci.appveyor.com/project/leonawicz/tiler) [![Coverage Status](https://img.shields.io/codecov/c/github/leonawicz/tiler/master.svg)](https://codecov.io/github/leonawicz/tiler?branch=master) [![gitter](https://img.shields.io/badge/GITTER-join%20chat-green.svg)](https://gitter.im/leonawicz/tiler) [![Join the chat at https://gitter.im/leonawicz/tiler](https://badges.gitter.im/leonawicz/tiler.svg)](https://gitter.im/leonawicz/tiler?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Create geographic and non-geographic map tiles
----------------------------------------------

The `tiler` package provides a tile generator function for creating map tile sets for use with packages such as `leaflet`. In addition to generating map tiles based on a common raster layer source, it also handles the non-geographic edge case, producing map tiles from arbitrary images. These map tiles, which have a "simple CRS", a non-geographic simple Cartesian coordinate reference system, can also be used with `leaflet` when applying the simple CRS option.

Map tiles can be created from a input file with any of the following extensions: `tif`, `grd` and `nc` for spatial maps and `png`, `jpg` and `bmp` for basic images.

Installation
------------

Install the development version from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("leonawicz/tiler")
```

### System requirements

This package requires Python and the `gdal` library for Python. Windows users are recommended to install [OSGeo4W](https://trac.osgeo.org/osgeo4w/) as an easy way to obtain the required `gdal` support for Python in Windows.

Examples
--------

See the [introduction vignette](https://leonawicz.github.io/tiler/articles/tiler.html) for more details and examples.

Reference
---------

[Complete package reference and function documentation](https://leonawicz.github.io/tiler/)

------------------------------------------------------------------------

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
