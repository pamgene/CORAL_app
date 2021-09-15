# CORAL

Trying to get [CORAL](http://phanstiel-lab.med.unc.edu/CORAL/) to work locally or as a PamApp in BioNavigator.
Forked from [dphansti/CORAL](https://github.com/dphansti/CORAL).

**Goals:**

- Allow input .txt from UKA without additional column selection<sup>1</sup> ✅
- Allow 2 .txts to be uploaded (e.g., for STK + PTK data) ✅
- Package as PamApp to be used in BioNavigator

<sup>1</sup> Currently set to `Median.Kinase.Statistic` for branch and node color and `Median.Final.score` for node size.

## Installation

1. First install `Rtools` on Windows: [Rtools download link](https://cran.r-project.org/bin/windows/Rtools/)
2. Open `CORAL.Rproj`
3. Run `renv::restore()` from the R Console (bottom-right part of the RStudio window)
4. Then start the Shiny server from either `ui.R` or `server.R`
