
<!-- README.md is generated from README.Rmd. Please edit that file -->

# nordicnoir

<!-- badges: start -->
<!-- badges: end -->

The goal of nordicnoir is to …

## Installation

You can install the development version of nordicnoir from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("taylorrodgers/nordic_noir")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(nordicnoir)
library(ggplot2)

ggplot(mtcars, aes(x = cyl, y = mpg, fill = factor(cyl))) +
  geom_boxplot() +
  nordic_fill_manual() +
  ggthemes::theme_pander()
```

<img src="man/figures/README-example-1.png" width="100%" />
