
# Repository `DOSI_NIHProposalProcessing`

This GitHub repository is made for storing the code and associated
documents for processing the National Institute of Health proposals that
are submitted at Duke University on a quarterly basis (e.g., Jan - Mar,
Apr - Jun, Jul - Sep, Oct - Dec). This code is made specifically for
processing the raw .csv files from the various internal websites at Duke
(e..g, SPS, RCR Tracker, LDap, etc.) and preparing the an import file
for the REDCap *Proposal Award Tracker*.

For those not affiliated with Duke University, this repository as a
whole will not be useful. However, the code may be helpful, and we
welcome and commits if errors found or ways for making the processing
more symplistic.

# License

<!-- TODO: Choose a license and update this section, if necessary -->

[Repository
DOSI_NIHProposalProcessing](https://github.com/wldkPHD/DOSI_NIHProposalProcessing)
© 2025 by [William L. D. Krenzer, Ph.D](https://github.com/wldkPHD) is
licensed under [CC BY-NC
4.0](https://creativecommons.org/licenses/by-nc/4.0). Please see the
[license file](LICENSE.md).

## Attributions

### Rstudio project template

This project makes use of the
[rproj-template](https://github.com/DaniMori/rproj-template) Github
template created by [Daniel Morillo](https://github.com/DaniMori) and
licensed under the [Creative Commons Attribution 4.0 International
license](https://creativecommons.org/licenses/by/4.0).

<!-- TODO: Add attributions to other software components, if necessary -->

### <Software component>

# Project installation

## Software components

Start by installing the following software components:

- [R version
  4.3.2](https://cran.rstudio.com/bin/windows/base/old/4.3.2/): In
  Windows, using the [binary
  installer](https://cran.rstudio.com/bin/windows/base/old/4.3.2/R-4.3.2-win.exe)
  is recommended.

<!-- -->

- [Rstudio Desktop](https://posit.co/download/rstudio-desktop/):
  Although not strictly necessary, it is recommended to install the
  Rstudio IDE; for strict reproducibility, use build [2025.05.1+513 for
  Windows
  10/11](https://download1.rstudio.org/electron/windows/RStudio-2025.05.1-513.exe).

<!-- -->

- [Quarto publishing system](https://quarto.org/): An additional
  component used by Rstudio to generate and publish literate computing
  outputs. For strict reproducibility please use build 1.6.42; On
  Windows, use [the 64-bit
  installer](https://github.com/quarto-dev/quarto-cli/releases/download/v1.6.42/quarto-1.6.42-win.msi).

<!-- -->

- [Git client](https://git-scm.com/download): Install the Git client in
  order to be able to clone locally the project repository. On Windows,
  use [the 64-bit Windows
  installer](https://github.com/git-for-windows/git/releases/download/v2.39.5.windows.1/Git-2.39.5-64-bit.exe).

# Repository structure

Below is a work in progress and has not yet been updated.

The file structure of this repository is as follows:

    DOSI_NIHProposalProcessing
    |
    |--- apps         (To store apps, e.g. in Shiny)
    |
    |--- dat          (To store input datasets; must NEVER be checked-in to Github)
    |
    |--- doc          (To store important documentation of the project)
    |    |
    |    |--- minutes (To store meeting minutes)
    |
    |--- notebooks    (Notebooks to explore data and test processes live here)
    |
    |--- output       (Processing outputs; files must be individually "checked-in"
    |                 when necessary)
    |
    |--- R            (R functions created for this project live here)
    |
    |--- renv         (System library necesssary for `renv` to work. DON'T TOUCH)
    |
    |--- src          (Source scripts that implement the main processes)
    |
    |--- www          (Project assets, e.g., images, bibliography files, etc.)

Use the folders as indicated to store the different files and generate
the outputs of the processes.
