# Pre-processing Tools for High-throughput Animal Tracking Data

<!-- badges: start -->
  [![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4033154.svg)](https://doi.org/10.5281/zenodo.4033154)
  [![R build status](https://github.com/pratikunterwegs/atlastools/workflows/R-CMD-check/badge.svg)](https://github.com/pratikunterwegs/atlastools/actions)
  [![codecov.io](https://codecov.io/github/pratikunterwegs/atlastools/coverage.svg?branch=master)](https://codecov.io/github/pratikunterwegs/atlastools/branch/master)
<!-- badges: end -->

`atlastools` is an `R` package to pre-process high frequency animal tracking data. 
It is written and maintained by [Pratik Gupte](https://www.rug.nl/staff/p.r.gupte), at the [University of Groningen's Theoretical Biology Group](https://www.rug.nl/research/gelifes/tres/). While aimed at data from ATLAS systems, it works with any `X, Y, TIME` data.

## Package documentation

The package functions are conveniently documented at the package website: https://pratikunterwegs.github.io/atlastools/

## A Guide to Pre-procesing High-throughput Animal Tracking Data

Using `atlastools` to clean data before making biological inferences is covered in this article in the _Journal of Animal Ecology_, [A Guide to Pre-processing High-throughput Animal Tracking Data](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.13610).

## Installation

```r
# This package can be installed using devtools
install.packages("devtools")

devtools::install_github("pratikunterwegs/atlastools")
```
