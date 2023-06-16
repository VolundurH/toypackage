
<!-- README.md is generated from README.Rmd. Please edit that file -->

# toypackage

<!-- badges: start -->
<!-- badges: end -->

The goal of toypackage is to make splitting strings easier

## Installation

You can install the development version of toypackage from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("VolundurH/toypackage")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(toypackage)

x <- "a,b,c"
str_split_one(x, pattern = ",")
#> [1] "a" "b" "c"
```
