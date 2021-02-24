
# ATI: Algorithmic trading and investment teaching resource

<!-- badges: start -->
<!-- badges: end -->

The goal of ATI is to help student learning about financial machine learning and its application to algorithmic trading and investment.

This package contains templates for reports, and functions and [`learnr`](https://rstudio.github.io/learnr/index.html) workshops using in [*Algorithmic trading and investment*](https://canvas.qub.ac.uk/courses/11744)) taught by [Barry Quinn](https://quinference.com/) inb Queen's Management School. 

``` r
remotes::install_github("barryquinn1/ATI")
```

You can start the tutorials in one of two ways. First, in RStudio 1.3 or later, you will find the ATI tutorials listed in the "Tutorial" tab in the top-right pane (by default). Find a tutorial and click "Run Tutorial" to get started. Second, you can run any tutorial from the R console by typing the following line: 

``` r
learnr::run_tutorial("Workshop2","ATI")
```

This should bring up a tutorial in your default web browser. You can see the full list of tutorials by running:

``` r
learnr::run_tutorial(package = "ATI")
```

## Critical Essay
This package also includes a RMarkdown template for use in the critical essay assessment.
Go to File>New>R Markdown... and choose from From Template then Report.
