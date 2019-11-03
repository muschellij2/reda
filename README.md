# reda

[![CRAN_Status_Badge][r-pkg-badge]][cran-url]
[![Build Status][travis-master]][travis]
[![AppVeyor Build Status][appveyor-master]][appveyor]
[![codecov][codecov-master]][codecov]

## Overview

The R package **reda** provides functions for

- simulating survival, recurrent event, and multiple event data from stochastic
  process point of view;
- exploring and modeling recurrent event data through the mean cumulative
  function (MCF) by the Nelson-Aalen estimator of the cumulative hazard rate
  function, and gamma frailty model with spline rate function;
- comparing two-sample recurrent event responses with the pseudo-score tests.


## Installation

You can install the released version from [CRAN][cran-url].

```R
install.packages("reda")
```


## Getting Started

- [Online documentation][homepage] provides function documentations and includes
  package vignettes for
  - [exploring and modeling recurrent event data][reda-intro].
  - [introduction to formula response function Recur()][reda-Recur]
  - [simulating survival and recurrent event data][reda-simulate].


## Development

The latest version of the package is under development at [GitHub][github-url].
If it is able to pass the building check by Travis CI, you may consider
installing it with the help of **remotes** by

```R
if (! require(remotes)) install.packages("remotes")
remotes::install_github("wenjie2wang/reda")
```


## License

The R package reda is free software: You can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation, either version 3 of the License, or any later version (at
your option).  See the [GNU General Public License][gpl-url] for details.

The R package reda is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.


[r-pkg-badge]: https://www.r-pkg.org/badges/version/reda
[cranlog-badge]: https://cranlogs.r-pkg.org/badges/splines2
[cran-url]: https://CRAN.R-project.org/package=reda
[travis]: https://travis-ci.org/wenjie2wang/reda
[travis-master]: https://travis-ci.org/wenjie2wang/reda.svg?branch=master
[appveyor]: https://ci.appveyor.com/project/wenjie2wang/reda
[appveyor-master]: https://ci.appveyor.com/api/projects/status/w6pr8b4clsnyfp32?svg=true
[github-url]: https://github.com/wenjie2wang/reda
[homepage]: https://wenjie-stat.me/reda/
[reda-intro]: https://wenjie-stat.me/reda/articles/reda-intro.html
[reda-Recur]: https://wenjie-stat.me/reda/articles/reda-Recur.html
[reda-simulate]: https://wenjie-stat.me/reda/articles/reda-simulate.html
[gpl-url]: https://www.gnu.org/licenses/
[codecov]: https://codecov.io/gh/wenjie2wang/reda
[codecov-master]: https://codecov.io/gh/wenjie2wang/reda/branch/master/graph/badge.svg
