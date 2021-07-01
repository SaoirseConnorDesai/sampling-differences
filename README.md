
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Individual differences in sensitivity to sampling effects

<!-- badges: start -->

<!-- badges: end -->

This repository contains material associated with:

  - Wen, Y. P., Desai, S. C., Navarro, D. J., & Hayes, B. K. (in
    preparation). *Who is sensitive to selection biases in inductive
    reasoning?*

The structure of this repository is based on Danielle Navarro’s
[cogsci-template](https://github.com/djnavarro/cogsci-template) and
roughly mirrors the conventions documented there. The substantive
content consists of the following folders, each with their own README.md
file:

  - [inputs](./inputs) contains the files I was provided with, unedited
  - [preprocessing](./preprocessing) contains an R script that reads
    input files, tidies and cleans the data, and exports the organised
    version of the files to the data folder
  - [data](./data) contains the cleaned data files as .csv files
  - [models](./models) contains an R script implementing the theoretical
    model
  - [analysis](./analysis) contains an R markdown document that analyses
    the data (from the data folder) with the assistance of the model
    (models folder)
  - [writeup](./writeup) does not contain the complete manuscript, only
    the technical appendix that describes the formal specification of
    the model
  - the [scratchpad.md](./scratchpad.md) file is essentially a manual
    log file, used for me to keep track of the process and take note of
    abandoned “forks” in the analysis process

The other files included in the repository are:

  - files allowing the R environment to be specified reproducibly using
    the  
    [renv package](https://rstudio.github.io/renv/): the [renv](./renv)
    folder and `renv.lock` file are the main ones, though note that renv
    also modifies the `.Rbuildignore` and `.Rprofile` files
  - project / repository management files: `sampling-differences.Rproj`
    and `.gitignore`.

The repository is not complete. Some things on the to-do list:

  - other resources (e.g., OSF folders, Overleaf documents, Google docs)
    that are linked to the project, should be linked from this readme
  - data files do not have a proper data dictionary yet
  - writeup files and the html output from the analysis folder should
    probably be made easily accessible via GH Pages
