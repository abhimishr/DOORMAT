
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Data Processor for IMPACT runs (DOORMAT)

<!-- badges: start -->

[![R-CMD-check](https://github.com/IFPRI/DOORMAT/actions/workflows/check-standard.yaml/badge.svg)](https://github.com/IFPRI/DOORMAT/actions/workflows/check-standard.yaml)
<!-- badges: end -->

DOORMAT (**D**ata pr**O**cessor f**O**R i**M**p**A**c**T**) is the core
R package which helps in compiling basic R functions to be able to
analyze some standard outputs from the the International Model for
Policy Analysis of Agricultural Commodities and Trade (IMPACT) model.

The IMPACT model was developed in the early 1990s to explore the long
term challenges facing policymakers in reducing hunger and poverty in a
sustainable fashion. The IMPACT model has been expanded and improved
repeatedly to respond to increasingly complex policy questions and the
state-of-the-art of modeling. [See documentation of most recent
update](http://www.ifpri.org/publication/international-model-policy-analysis-agricultural-commodities-and-trade-impact-model-0).

The goal of DOORMAT is to to be able to setup some standar functions
which will help in reading the outputs from a *gdx* file belonging to
the outputs of an IMPACT run. The package also provides a `buildPackage`
utility which helps in compiling the packages from the IMPACT
R-universe.

## Installation

You can install the latest version of DOORMAT from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("IFPRI/DOORMAT")
```

## Questions / Problems

In case of questions / problems please contact Abhijeet Mishra
(<A.Mishra@cgiar.org>)
