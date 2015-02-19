---
title       : Testing Slidify
subtitle    : A dumping ground where I test out new styles of Slidify
author      : Stat 217
date        : today
framework   : bootstrap3
highlighter : highlight.js  
hitheme     : tomorrow      
widgets     : []
layout      : deck3
mode        : selfcontained 
knit        : slidify::knit2slides
assets      : 
  css       : 
    - "assets/css/table-styles.css"
    - "assets/css/custom.css"
    - "assets/css/moving_sidebar.css"
    - "http://fonts.googleapis.com/css?family=Vollkorn"
    - "http://fonts.googleapis.com/css?family=Droid%20Sans%20Mono"
---



## Introduction

This is where I test out new slidify layouts!

---
## An example plot

Using the `cars` data in R


```r
plot(dist ~ speed, data = cars)
```

<img src="assets/fig/cars-plot-1.png" title="plot of chunk cars-plot" alt="plot of chunk cars-plot" style="display: block; margin: auto;" />


