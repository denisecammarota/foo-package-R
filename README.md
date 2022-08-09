
<!-- README.md is generated from README.Rmd. Please edit that file -->

# foo

<!-- badges: start -->

[![R-CMD-check](https://github.com/denisecammarota/foo-package-R/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/denisecammarota/foo-package-R/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of foo is to exemplify the creation of an R package. In this
case, this package has only a function called ‘my_shannon’ that
calculates the Shannon diversity index from a vector.

## Installation

You can install the development version of foo like so:

``` r
remotes::install_github("denisecammarota/foo-package-R")
#> Downloading GitHub repo denisecammarota/foo-package-R@HEAD
#> * checking for file 'C:\Users\denis\AppData\Local\Temp\RtmpK6edBp\remotes44783d8a3848\denisecammarota-foo-package-R-7263046/DESCRIPTION' ... OK
#> * preparing 'foo':
#> * checking DESCRIPTION meta-information ... OK
#> * checking for LF line-endings in source and make files and shell scripts
#> * checking for empty or unneeded directories
#> * building 'foo_0.0.0.9000.tar.gz'
#> 
#> Installing package into 'C:/Users/denis/AppData/Local/R/win-library/4.2'
#> (as 'lib' is unspecified)
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(foo)
shannon_index <- my_shannon(c(1,2,3)) #calculate shannon diversity index
```
