# r-course-exercise

<!-- badges: start -->
[![Project Status: Inactive – The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](https://www.repostatus.org/badges/latest/inactive.svg)](https://www.repostatus.org/#inactive)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
<!-- badges: end -->

## Overview

🧒🏽🇧🇷🍔🍟🍕🍫🍭🍬🍿🥤🍩🍪🍰🧃

This repository contains a data analysis exercise for the course [An Introduction to the R Programming Language](https://github.com/danielvartan/r-course).

The report investigates differences in ultra-processed food consumption among Brazilian children aged 2 to 4 in 2022. The analysis focuses on clusters B and D of the Revised Multidimensional Index for Sustainable Food Systems ([MISFS-R](https://doi.org/10.1002/sd.2376)). You can view the full report [here](https://danielvartan.github.io/r-course-exercise/).

## How to Use

The analyses contained in the report are fully reproducible. They were made using the [R programming language](https://www.r-project.org/) and the [Quarto](https://quarto.org/) publishing system. The [`renv`](https://rstudio.github.io/renv/) package was used to ensure that the R environment used can be restored (see `renv.lock`).

To reproduce the analyses do the following steps:

1. Clone this repository.
1. Open the R project in your IDE of choice.
1. Run [`renv::restore()`](https://rstudio.github.io/renv//reference/restore.html) to install all software dependencies.
1. Open `index.qmd` and run the analyses.

## License

[![License:
MIT](https://img.shields.io/badge/license-MIT-green.png)](https://opensource.org/license/mit)
[![License: CC BY
4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

The code in this repository is licensed under the [MIT
License](https://opensource.org/license/mit/), while the documents are available under the [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).

## How to Cite

To cite this work, please use the following format:

Vartanian, D., & Pereira, J. L. (2025). *An introduction to the R programming language: Class exercise* \[Report\]. Sustentarea Research and Extension Group at the University of São Paulo. <https://danielvartan.github.io/r-course-exercise/>

A BibTeX entry for LaTeX users is

```
@techreport{vartanian2025,
  title = {An introduction to the R programming language: Class exercise},
  author = {{Daniel Vartanian} and {Jaqueline Lopes Pereira}},
  year = {2025},
  address = {São Paulo},
  institution = {Sustentarea Research and Extension Group at the University of São Paulo},
  langid = {en},
  url = {https://danielvartan.github.io/r-course-exercise/}
}
```
