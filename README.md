# epistasis

Detection of epistatic selection from partially observed genotype data by reconstructing a network of marker-marker associations.

Compatibility updates by Renova.

Version 0.0.1.1.9001 makes the `class()` checks in `model.selection()` safe for objects with several classes, fixes Rd markup in three help pages (literal braces, a missing backslash and a missing `\alias`), and updates `DESCRIPTION` metadata: an `Authors@R` entry equivalent to the existing authors and maintainer, and removal of the stale optional `Date` field.

## Install

```r
install.packages("epistasis", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/epistasis@renova-0.0.1.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

epistasis is by Pariya Behrouzi (maintainer), Danny Arends and Ernst C. Wit; the original CRAN package is at <https://CRAN.R-project.org/package=epistasis>. License: GPL-3; see [COPYING](COPYING).
