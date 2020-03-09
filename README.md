
<!-- README.md is generated from README.Rmd. Please edit that file -->

# BRGenomics

<!-- badges: start -->

<!-- badges: end -->

Efficient tools for the analysis of high-resolution genomics data in R.

Explore the documentation: <https://mdeber.github.io/>

## Installation

Install development version from
[GitHub](https://github.com/mdeber/BRGenomics):

``` r
# install.packages("remotes")
remotes::install_github("mdeber/BRGenomics@R3")
```

*The `@R3` branch will install under R version \>=3.5, while the main
branch requires R 4.0, which is still under development.*

If you’re using Windows, [Rtools for
Windows](https://cran.rstudio.com/bin/windows/Rtools/) is required.

## Features

See the [documentation website](https://mdeber.github.io/), which
includes an introductory vignette, as well as the documentation for
currently implemented functions, complete with demonstrative example
code. The package currently includes example PRO-seq
data<sup>\[1\]</sup>.

## Limitations for Windows users

  - Currently no support for parallel/multicore processing
  - No support for import bigWig files

## To Do

  - Convert method dispatch to S4 generics
  - Formalize support for `GRangesList` objects (progress underway)
  - Write methods for `BigWigFile`/`BigWigFileList` objects (to avoid
    loading data into memory)
  - (Possibly) use `GPos` objects by default

-----

1.  Hojoong Kwak, Nicholas J. Fuda, Leighton J. Core, John T. Lis
    (2013). Precise Maps of RNA Polymerase Reveal How Promoters Direct
    Initiation and Pausing. *Science* **339**(6122): 950–953.
    <https://doi.org/10.1126/science.1229386>
