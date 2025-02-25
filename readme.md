# FUSE

## Table of Contents

- [About](#about)
- [Getting Started and Usage](#getting_started_and_usage)
- [Tests or Validation](#tests)
- [License](#license)
- [Get Help](#help)


## About <a name = "about"></a>

This repo contains the Fortran code for the **Framework for Understanding Structural Errors** or **FUSE**. FUSE is modular modelling framework which enables the generation of a myriad of conceptual hydrological models by recombining elements from commonly-used models. FUSE is a community model and is published under a **GPLv3 license**.

### FUSE motivation

Running a hydrological model means making a wide range of decisions, which will influence the simulations in different ways and to different extents. Our goal with FUSE is enable users to be in charge of these decisions, so that they can understand their effects, and thereby, develop and use better models.

FUSE was build from scratch to be modular, it offers several options for each important modelling decision and enables the addition of new modules. In contrast, most traditional hydrological models rely on a single model structure (most processes are simulated by a single set of equations). FUSE modularity makes it easier to i) understand differences between models, ii) run a large ensemble of models, iii) capture the spatial variability of hydrological processes and iv) develop and improve hydrological models in a coordinated fashion across the community.

### New features

FUSE initial implementation (FUSE1) is described in [Clark et al. (WRR, 2008)](http://dx.doi.org/10.1029/2007WR006735). The implementation provided here (which will become FUSE2) was created with users in mind and significantly increases the usability and range of applicability of the original version. In particular, it involves 5 main additional features:

- an interface enabling the use of the different FUSE modes (default, calibration, regionalisation),
- a distributed mode enabling FUSE to run on a grid whilst efficiently managing memory,
- all the input, output and parameter files are now NetCDF files to improve reproducibility,
- a calibration mode based on the shuffled complex evolution algorithm (Duan et al., WRR, 1992),
- a snow module described in Henn et al. (WRR, 2015).


## Getting Started and Usage <a name = "#getting_started_and_usage"></a>

### Prerequisites and installation

See the installation page of the [FUSE manual](https://naddor.github.io/fuse/).

### How to run the code

See the execution section of the [FUSE manual](https://naddor.github.io/fuse/).

## Tests or Validation<a name = "tests"></a>

Scripts to evaluate FUSE simulations are provided by the separate [fuse_deployment](https://github.com/fathom-global/fuse_deployments) repo.

## License <a name = "license"></a>

FUSE is distributed under the GNU Public License Version 3. For details see the file `LICENSE` in the FUSE root directory or visit the [online version](http://www.gnu.org/licenses/gpl-3.0.html).

## Maintainers<a name = "help"></a>

Nans Addor
