
<!-- README.md is generated from README.Rmd. Please edit that file -->

# burnishingtoolstraces

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jmmarreiros/burnishingtoolstraces/master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Laure Debreuil, Jérôme Robitaille, Jesus Gonzalez-Urquijo, Joao
> Marreiros, Anna Stroulia. 2023.
> *`A ‘Family of Wear’: Traceological Patterns on Pebbles Used for Burnishing Pots and Processing Other Plastic Mineral Matters`*.
> Journal of Archaeological Theory and Method
> <https://doi.org/10.1007/s10816-022-09597-z>

### How to cite

Please cite this compendium as:

> Laure Debreuil, Jérôme Robitaille, Jesus Gonzalez-Urquijo, Joao
> Marreiros, Anna Stroulia, (2022). *Compendium of R code and data for A
> ‘Family of Wear’: Traceological Patterns on Pebbles Used for
> Burnishing Pots and Processing Other Plastic Mineral Matters*.
> Accessed 20 Dec 2022. Online at
> <https://doi.org/10.5281/zenodo.5607062>

## Contents

The **analysis** directory contains:

- [:file_folder: derived_data](/analysis/derived_data): Data used in the
  analysis.
- [:file_folder: raw_data](/analysis/raw_data): raw data.
- [:file_folder: plots](/analysis/plots): Plots and other illustrations
- [:file_folder: summary_stats](/analysis/summary_stats): summary of
  data descriptive analysis.
- [:file_folder: scripts](/analysis/scripts): scripts.

## How to run in your broswer or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

The simplest way to explore the text, code and data is to click on
[binder](https://mybinder.org/v2/gh/jmmarreiros/burnishingtoolstraces/master?urlpath=rstudio)
to open an instance of RStudio in your browser, which will have the
compendium files ready to work with. Binder uses rocker-project.org
Docker images to ensure a consistent and reproducible computational
environment. These Docker images can also be used locally.

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.Rmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.
