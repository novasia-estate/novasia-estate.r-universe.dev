# NovAsia Estate R-universe

Organization-owned registry for the R packages maintained by [NovAsia Estate](https://novasia.estate/).

The registry belongs to `github.com/novasia-estate/novasia-estate.r-universe.dev`; the intended native universe is `https://novasia-estate.r-universe.dev`. It does not use a personal GitHub namespace.

## Packages

- **propertycohorts** — [Property Cohort Audit](https://github.com/novasia-estate/property-cohort-audit): a descriptive audit of listing-snapshot comparability, coverage and composition effects. Includes an invented reproducible scenario and local reports; it does not estimate a market index.

```r
install.packages("propertycohorts", repos = c(
  "https://novasia-estate.r-universe.dev", "https://cloud.r-project.org"
))
```

`packages.json` is the canonical registry input. Native availability follows successful R-universe processing; a GitHub push alone does not prove that a native build or installation is ready.
