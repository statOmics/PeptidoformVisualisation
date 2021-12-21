# PeptidoformVisualisation
R package for launching shiny app

# The package
This R package contains all code to launch a shiny app for the visualisation of quantitative peptidoform data. 
The user can upload a peptide intensity file and a metadata file containing information about the experiment setup. 
With the app, the user can perform preprocessing (normalisation, log transformation) and visualise the intensity data.

# How to install
In RStudio (or another IDE), use 

```
devtools::install_github("ndmeulem/PeptidoformVisualisation") 
```

This will install the package and its dependencies.

# How to use
To load package: 

```
library(PeptidoformVisualisation)
```

To launch shiny app, use: 

```
launchPeptidoformVisualisation()
```