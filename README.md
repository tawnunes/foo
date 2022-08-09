
<!-- README.md is generated from README.Rmd. Please edit that file -->

# foo

<!-- badges: start -->
<!-- badges: end -->

The goal of foo is to calculate Shannon diversity index

## Installation

You can install the development version of foo like so:

``` r
remotes::install_github("tawnunes/foo")
```

## Example


```{r example}
library(foo)

community <- c(1, 2, 3) # abundances of the species in the community
my_shannon(community)
```

