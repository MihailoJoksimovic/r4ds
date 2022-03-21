# R for Data Science

[![Travis build status](https://travis-ci.org/hadley/r4ds.svg?branch=master)](https://travis-ci.org/hadley/r4ds)

This repository contains the source of [R for Data Science](http://r4ds.had.co.nz) book.
The book is built using [bookdown](https://github.com/rstudio/bookdown).

The R packages used in this book can be installed via

```{r}
devtools::install_github("hadley/r4ds")
```

## Images

### Omnigraffle drawings

-   Font: 12pt Ubuntu mono
-   Export as 300 dpi png.
-   Website font is 18 px = 13.5 pt, so scale dpi to match font sizes: 270 = 300 \* 12 / 13.5
-   Verified sizes are visually equivalent by screenshotting.

```{=html}
<!-- -->
```
    #| echo: FALSE
    #| out.width: NULL
    #| fig.retina: 1.5
    knitr::include_graphics("diagrams/transform.png", dpi = 270)

## Code of Conduct

Please note that r4ds uses a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this book, you agree to abide by its terms.
