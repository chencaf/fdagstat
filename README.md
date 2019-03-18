# fdagstat

The 'fdagstat' R package implements the recently developed methods of geostatistics for functional data. The methods implemented up to date are as follows:

# Implemented methods

1. Universal trace kriging by [Menafoglio et al (2013)](https://projecteuclid.org/euclid.ejs/1379596770)
2. Ordinary trace kriging by [Giraldo et al (2011)](https://link.springer.com/article/10.1007/s10651-010-0143-y)
3. Universal trace co-kriging by [Grujic et al (2017)]( https://doi.org/10.1007/s00477-017-1486-9)
4. Ordinary co-kriging of fpc scores by [Nerini et al (2010)]( http://www.sciencedirect.com/science/article/pii/S0047259X0900061X)
5. Universal co-kriging of fpc scores by [Menafoglio et al (2016)](http://www.sciencedirect.com/science/article/pii/S2211675315001141)
6. Universal co-kriging of fpc scores of multivariate functional data by [Bohorquez et al (2016)](http://dx.doi.org/10.1007/s00477-016-1266-y)

The package is also capable of fitting conventional scalar geostatistical models such as universal and ordinary kriging and co-kriging. In the current version, the package does not implement simple kriging or any form of sequential Gaussian simulation.

## Installing from GitHub

To install the package, first install `devtools` (`install.packages("devtools")`), then copy paste the following code into your `R/Rstudio` command line

```{R}
devtools::install_github("ogru/fdagstat")
```

After installing, you can add the library to your project/script in the conventional manner with `library(fdagstat)`.

## Tutorials

To see some of the capabilities of the package and/or get started with using the package, please view the vignette at the following [link](https://rawgit.com/ogru/fdagstat/master/vignette/First_Steps_With_fdagstat.html) (it opens inside your web-browser, no need to download!)

A new vignette! Shale modeling with `fdagstat` [(link)](https://rawgit.com/ogru/fdagstat/master/vignette/Shale_Modeling_with_fdagstat.html)

Note: If you are using Safari web browser, some formulas might not display correctly. I recommend that you use Firefox or Chrome to view the vignettes.

## License
The package is distributed under the terms of the GPL-2 license (see LICENSE.txt).


If you encounter any error(s) while installing or using the package, please feel free to raise an issue at the repo or send an e-mail to ognjengr@gmail.com

## Citation

If you find this package useful in your work, please consider citing it in your publication(s) with the following Bibtex entry:
```
@Manual{fdagstat_2017,
  title  = {fdagstat, an \proglang{R} package},
  author = {Ognjen Grujic and Alessandra Menafoglio},
  year   = {2017},
  note   = {\proglang{R}~package version~1.0},
  url    = {https://github.com/ogru/fdagstat},
}
```
