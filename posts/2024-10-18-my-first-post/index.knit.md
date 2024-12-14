---
title: "Predictors of food security and affordability in California"
description: "In this blog I explore how geography and socio-economic factors influence annual food costs in female-headed households."
author:
  - name: Kaiju Morquecho Rubalcava
    affiliation: MEDS Graduate Student
    affiliation-url: https://bren.ucsb.edu/masters-programs/master-environmental-data-science/academics-meds-program
date: 2024-12-13
bibliography: references.bib
image: sketches.jpeg
citation:
  url: https://kaimorquecho.github.io/posts/2024-10-18-my-first-post/
draft: FALSE
draft-mode: visible 
---



## *Why food affordability?*

My initial project proposal sought to investigate the correlations between food insecurity and gender identity in Mexico using INEGI data. However, the datasets of interest were virtually impossible to join based on geography. Furthermore, the datasets available to download were limited to certain years and only certain sections of the surveys of my interest (ENSANUT and ENDISEG).

Instead, I am analyzing food affordability data from California, specifically that of female-headed households, across CA regions. This project is only a starting point in exploring the challenges and systemic obstacles faced by female-identifying heads of households. In fact, the main learning outcome of the project, as I will show below, is that almost any environmental issue, including food security, requires a nuanced & complex understanding of its origin for there to be a just solution to it.

If you are interested in exploring Mexico's first gender non-conforming census survey, check out this page! [^1]

[^1]: [INEGI ENDISEG](https://en.www.inegi.org.mx/programas/endiseg/2021/)

## Now, let's dive into the data!

##### *Data description*

-   The data set was created by the U.S Department of Public Health, using data from:

    -   U.S Census Bureau's American Community Survey (CA households and family data, and median income data)\[\]

    -   U.S Department of Agriculture's Economic Research Reserve (annual food cost data)

    -   Office of Health Equity's Healthy Communities Data and Indicators Project (food affordability ratio)

Here's my next paragraph[^2]

[^2]: here is my second footnote

I'm citing me[@csik2022]



::: {.cell}
::: {.cell-output .cell-output-stderr}

```
── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
✔ dplyr     1.1.4     ✔ readr     2.1.5
✔ forcats   1.0.0     ✔ stringr   1.5.1
✔ ggplot2   3.5.1     ✔ tibble    3.2.1
✔ lubridate 1.9.3     ✔ tidyr     1.3.1
✔ purrr     1.0.2     
── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
✖ dplyr::filter() masks stats::filter()
✖ dplyr::lag()    masks stats::lag()
ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors
```


:::

::: {.cell-output-display}
![](index_files/figure-html/unnamed-chunk-1-1.png){width=672}
:::
:::

