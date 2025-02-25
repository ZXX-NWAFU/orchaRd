# Introducing the Orchard Plot for Meta-analysis
[![Build Status](https://app.travis-ci.com/daniel1noble/orchaRd.svg?branch=main)](https://app.travis-ci.com/daniel1noble/orchaRd.svg?branch=main) 
[![codecov](https://codecov.io/gh/daniel1noble/orchaRd/branch/main/graph/badge.svg?token=KqQLvcGfLv)](https://codecov.io/gh/daniel1noble/orchaRd)
[![Ask Us Anything\ !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/daniel1noble/orchaRd/issues/new)
![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)

# Citing orchaRd

To cite `orchaRd` in publications one can use the following reference:

Nakagawa, S., Lagisz, M., O'Dea, R. E., Rutkowska, J., Yang, Y., Noble, D. W., & Senior, A. M. (2019). The Orchard Plot: Cultivating Forest Plots for Use in Ecology, Evolution and Beyond. *Research Synthesis Methods* https://doi.org/10.1002/jrsm.1424 12: 4-12 (preprint = *EcoEvoRxiv* https://doi.org/10.32942/osf.io/epqa7)

# Installation

To install `orchaRd` use the following code in R:

```
install.packages("pacman")
pacman::p_load(devtools, tidyverse, metafor, patchwork, R.rsp, emmeans)

devtools::install_github("daniel1noble/orchaRd", force = TRUE)
library(orchaRd)

```

# How to use?
We detail how to use `orchaRd` function in the [vignette](https://daniel1noble.github.io/orchaRd/). 
