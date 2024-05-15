# ACIC 2024 BART Workshop Materials

This repository hosts slides, data, and vignettes from the 2024 ACIC BART Workshop.

## Software dependencies

### StochasticTree package

The `stochtree` R package is hosted on [Github](https://github.com/StochasticTree/stochtree-r) 
and has a [Github pages docsite](https://stochastictree.github.io/stochtree-r/).

The package is not [*yet!*] on CRAN, but can be installed directly from Github with 
the `remotes` package as follows

```{r}
# install.packages("remotes")
remotes::install_github("StochasticTree/stochtree-r")
```

Refer to the [documentation site](https://stochastictree.github.io/stochtree-r/) 
for function / class documentation and feature demos.

### Possum package

The possum (POSterior SUMmarization) package is also available on Github and 
can be installed via `remotes::install_github`

```{r}
remotes::install_github("spencerwoody/possum")
```

### Other dependencies

The vignettes require several other packages which can be installed from CRAN

```{r}
pkg_list <- c("ggplot2", "latex2exp", "coda", "rpart", "rpart.plot", "tidyverse", "here")
install.packages(pkg_list)
```
