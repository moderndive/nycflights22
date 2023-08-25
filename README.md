# nycflights22
An R data package containing all out-bound flights from NYC in 2022 + useful metadata

This package was created using the [`anyflights`](https://github.com/simonpcouch/anyflights) R package. Additional data preparation was done to include additional rows of data instead of missing entries in the `weather` data frame.

### Installation

------------------------------------------------------------------------

To install the current stable version of `nycflights22`, make sure to
install `remotes` first. The `pkgdown` website for this version is at
[moderndive.github.io/nycflights22](https://moderndive.github.io/nycflights22).

``` r
# install.packages("remotes")
remotes::install_githubk("moderndive/nycflights22")
