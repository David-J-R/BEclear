[![Travis-CI Build Status](https://travis-ci.org/David-J-R/BEclear.svg?branch=master)](https://travis-ci.org/David-J-R/BEclear)
[![Coverage Status](https://img.shields.io/codecov/c/github/David-J-R/BEclear/master.svg)](https://codecov.io/github/David-J-R/BEclear?branch=master)


# BEclear

## Description

This package provides functions to detect and correct for batch effects in
DNA methylation data. The core function for the data imputation is based on 
latent factor models and can also be used to predict missing values in any other 
matrix containing real numbers.

## Installation

```r
# Installation from Bioconductor
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("BEclear")
```

```r
# Installation of the development version from GitHub
if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")

devtools::install_github("David-J-R/BEclear", build_vignettes=TRUE)
```

## Usage example

coming soon...

## Citation

Akulenko, R., Merl, M., & Helms, V. (2016). BEclear: Batch effect detection and 
adjustment in DNA methylation data. PLoS ONE, 11(8), 1–17.
[DOI:10.1371/journal.pone.0159921](https://doi.org/10.1371/journal.pone.0159921)
