
<!-- README.md is generated from README.Rmd. Please edit that file -->

# psr

<!-- badges: start -->

<!-- badges: end -->

## Description

The goal of psr is to help practitioners in the field of sports science,
whether it be coaches, athletic trainers, analysts, or even athletes
themselves, to efficiently and effectively analyze data from strength
and agility tests. This package includes seven functions that measure
the reliability of the measurement instruments involved in testing the
athletes, setting benchmarks for each athlete in their future tests, and
standardizing the scores of the athletes on a team across metrics.

## Installation

You can install the released version of psr from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("psr")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("tommy-mcginn/Performance-Science-Reliability")
```

## Structure

The package includes seven functions, which can be grouped into the
following categories:

  - Reliability Functions \*\* Typical Error: TE() \*\* Coefficient of
    Variation: CV() \*\* Standard Error of Measurement: SEM() \*\*
    Intra-class Correlation Coefficient (in long form): ICC\_long()

  - Individual Change Functions \*\* Smallest Worthwhile Change: SWC()
    \*\* Minimal Detectable Change: MDC()

  - Standardization of Data Functions: \*\* Standard Ten Scores: STEN()

The package does not include any data, but there is one vignette for the
package, which describes each of these functions in detail, shows how
they can be used with example data, and explains possible errors that
the user could make and how each function in the package delivers an
informative, specialized error message to the user when any of these
errors are made.
