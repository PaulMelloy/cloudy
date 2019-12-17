# cloudy

<!-- badges: start -->
[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

The goal of cloudy is to import data from  AARNET Cloudstor, OneDrive,
Sharepoint, GDrive, GitHub or any other web-based provider serving a file via
a downloadable URL.

## Installation

You can install cloudy from [GitHub](https://github.com/adamhsparks/cloudy) with:

``` r
devtools::install_github("adamhsparks/cloudy")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(cloudy)
P_sojae <-
  fetch_data(url = "https://raw.githubusercontent.com/openplantpathology/hagis/master/inst/extdata/practice_data_set.csv")
```

# Meta

Please note that the 'cloudy' project is released with a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md). By contributing to this project, you agree
to abide by its terms.
