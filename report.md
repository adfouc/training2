Report on Gun Murders
================
Rafael Irizarry
2020-02-25

## Introduction

This is a report on 2010 gun murder rates obtained from FBI reports. The
original data was obtained from [this Wikipedia
page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state).

We are going to use the following library:

``` r
library(tidyverse)
```

and load the data we already wrangled:

``` r
load("rda/murders.rda")
```

## Murder rate by state

We note the large state to state variability by generating a barplot
showing the murder rate by state:

![](report_files/figure-gfm/murder-rate-by-state-1.png)<!-- -->

<!-- test -->

``` r
n <- 25
n
```

    ## [1] 25

Here 25 cars are compared

<!-- test  -->

`{r eval=FALSE) a <- 2`

    ## [1] 6

    ## [1] 34

    ## [1] 35
