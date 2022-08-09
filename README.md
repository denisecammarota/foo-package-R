
<!-- README.md is generated from README.Rmd. Please edit that file -->

# foo

<!-- badges: start -->
<!-- badges: end -->

The goal of foo is to exemplify the creation of an R package. In this
case, this package has only a function called ‘my_shannon’ that
calculates the Shannon diversity index from a vector.

## Installation

You can install the development version of foo like so:

``` r
remotes::install_github("denisecammarota/foo-package-R")
#> Skipping install of 'foo' from a github remote, the SHA1 (25ddd1d3) has not changed since last install.
#>   Use `force = TRUE` to force installation
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(foo)
shannon_index <- my_shannon(c(1,2,3)) #calculate shannon diversity index
```
