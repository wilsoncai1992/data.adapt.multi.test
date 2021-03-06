
<!-- README.md is generated from README.Rmd. Please edit that file -->

# R/`adaptest`

[![Travis-CI Build
Status](https://travis-ci.org/wilsoncai1992/adaptest.svg?branch=master)](https://travis-ci.org/wilsoncai1992/adaptest?branch=master)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/wilsoncai1992/adaptest?branch=master&svg=true)](https://ci.appveyor.com/project/wilsoncai1992/adaptest/)
[![Coverage
Status](https://img.shields.io/codecov/c/github/wilsoncai1992/adaptest/master.svg)](https://codecov.io/github/wilsoncai1992/adaptest?branch=master)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![BioC
status](http://www.bioconductor.org/shields/build/release/bioc/adaptest.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/adaptest)
[![Bioc
Time](http://bioconductor.org/shields/years-in-bioc/adaptest.svg)](https://bioconductor.org/packages/release/bioc/html/adaptest.html)
[![Bioc
Downloads](http://bioconductor.org/shields/downloads/adaptest.svg)](https://bioconductor.org/packages/release/bioc/html/adaptest.html)
[![GPL-2
License](http://img.shields.io/:license-gpl2-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![Zenodo
DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1466019.svg)](https://doi.org/10.5281/zenodo.1466019)
[![JOSS Status and
DOI](http://joss.theoj.org/papers/10.21105/joss.00161/status.svg)](https://doi.org/10.21105/joss.00161)

> Data-adaptive statistics for multiple testing in high-dimensional
> biology

**Authors:** [Wilson Cai](https://stat.berkeley.edu/~wcai) and [Nima
Hejazi](https://nimahejazi.org)

-----

## What’s `adaptest`?

The `adaptest` R package is a tool for performing multiple testing on
effect sizes in high-dimensional settings, using the approach of
data-adaptive statistical target parameters and inference. For technical
details on the data-adaptive multiple testing procedure, consult Cai,
Hejazi, and Hubbard (n.d.). For an introduction to statistical inference
procedures using data-adaptive target parameters, the interested reader
is directed to Hubbard, Kherad-Pajouh, and van der Laan (2016).

-----

## Installation

For standard use, install from
[Bioconductor](https://bioconductor.org/packages/adaptest) using
[`BiocManager`](https://CRAN.R-project.org/package=BiocManager):

``` r
if (!requireNamespace("BiocManager", quietly=TRUE)) {
    install.packages("BiocManager")
}
BiocManager::install("adaptest")
```

To contribute, install the *development version* (i.e., branch
**`master`**) from GitHub via
[`devtools`](https://www.rstudio.com/products/rpackages/devtools/):

``` r
devtools::install_github("wilsoncai1992/adaptest")
```

Current and prior [Bioconductor](https://bioconductor.org) releases are
available under branches with numbers prefixed by “RELEASE\_”. For
example, to install the version of this package available via
Bioconductor 3.7, use

``` r
devtools::install_github("wilsoncai1992/adaptest", ref = "RELEASE_3_7")
```

***Note*: As the first stable release of this package was through
Bioconductor v3.7, the minimum version of
[R](https://www.r-project.org/) required to install `adaptest` is 3.5.0
(codename “Joy in Playing”).**

-----

## Example

For details on how to best use the `adaptest` R package, please consult
the most recent [package
vignette](https://bioconductor.org/packages/release/bioc/vignettes/adaptest/inst/doc/differentialExpression.html)
available through the [Bioconductor
project](https://bioconductor.org/packages/adaptest).

-----

## Issues

If you encounter any bugs or have any specific feature requests, please
[file an issue](https://github.com/wilsoncai1992/adaptest/issues).

-----

## Contributions

Contributions are very welcome. Interested contributors should consult
our [contribution
guidelines](https://github.com/wilsoncai1992/adaptest/blob/master/CONTRIBUTING.md)
prior to submitting a pull request.

-----

## Citation

After using the `adaptest` R package, please cite the following

``` 
  @article{cai2018adaptest,
    doi = {10.21105/joss.00161},
    url = {https://doi.org/10.21105/joss.00161},
    year  = {2018},
    month = {October},
    publisher = {The Open Journal},
    volume = {3},
    number = {30},
    author = {Cai, Weixin and Hubbard, Alan E and Hejazi, Nima S},
    title = {{adaptest}: Data-Adaptive Statistics for High-Dimensional
      Testing in {R}},
    journal = {The Journal of Open Source Software}
  }

  @article{cai2018+adaptive,
    url = {https://arxiv.org/abs/1704.07008},
    year  = {2018+},
    author = {Cai, Weixin and Hejazi, Nima S and Hubbard, Alan E},
    title = {Data-adaptive statistics for multiple hypothesis testing in
      high-dimensional settings}
  }
```

-----

## Funding

The development of this software was supported in part through grants
from the National Institutes of Health: [P42
ES004705-29](https://projectreporter.nih.gov/project_info_details.cfm?aid=9260357&map=y)
and [T32
LM012417-02](https://projectreporter.nih.gov/project_info_description.cfm?aid=9248418&icde=37849831&ddparam=&ddvalue=&ddsub=&cr=1&csb=default&cs=ASC&pball=).

-----

## License

© 2017-2018 [Wilson Cai](https://statistics.berkeley.edu/~wcai)

The software contents of this repository are distributed under the GPL-2
license. See file `LICENSE` for details.

-----

## References

<div id="refs" class="references">

<div id="ref-cai2018data">

Cai, Weixin, Nima S Hejazi, and Alan E Hubbard. n.d. “Data-Adaptive
Statistics for Multiple Hypothesis Testing in High-Dimensional
Settings.” <https://arxiv.org/abs/1704.07008>.

</div>

<div id="ref-hubbard2016statistical">

Hubbard, Alan E, Sara Kherad-Pajouh, and Mark J van der Laan. 2016.
“Statistical Inference for Data Adaptive Target Parameters.” *The
International Journal of Biostatistics* 12 (1): 3–19.

</div>

</div>
