 # Introduction of Stat302Package: 
This package is created as a class project for Stat302 in UW. It contains four formulas: my_t_test, my_lm, my_knn_cv, and my_rf_cv. This package is collabrated by Celeste Zeng and Simona Liao

  <!-- badges: start -->
  [![Travis build status](https://travis-ci.com/SimonaLiao/Stat302Package.svg?branch=master)](https://travis-ci.com/SimonaLiao/Stat302Package)
  [![Codecov test coverage](https://codecov.io/gh/SimonaLiao/Stat302Package/branch/master/graph/badge.svg)](https://codecov.io/gh/SimonaLiao/Stat302Package?branch=master)
  <!-- badges: end -->

# Installation
To download the Stat302 package, use the code below.

```{r}
# install.packages("devtools")
devtools::install_github("SimonaLiao/Stat302Package")
library(Stat302Package)
```
# Use
The vignette demonstrates example usage of all main functions. You can see the vignette by using the following code:

```{r}
# install.packages("devtools")
devtools::install_github("SimonaLiao/Stat302Package", build_vignette = TRUE, build_opts = c())
library(Stat302Package)
# Use this to view the vignette in the Demo HTML help
help(package = "Stat302Package", help_type = "html")
# Use this to view the vignette as an isolated HTML file
utils::browseVignettes(package = "Stat302Package")
```



