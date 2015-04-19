---
title       : Births vs. Deaths Pitch
subtitle    : A shiny app for exploring the relationship between births and deaths across the world.
author      : Sebastian Stoll
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



# Importance of understanding the demographic developments

The demographic development within a country or region is fundamental for decision making. For example an aging and declining population requires different strategies than a population which is getting younger.

Especially in developed countries there is a steady decline of population e.g. in Germany:

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- .class #id 

# Births vs. Deaths App

Births vs. Deaths is an app to interactively explore the relationship between births and deaths in a selected country or region.

It is hosted on shinyapps.io and can be reached under the URL 

https://sebastianstoll.shinyapps.io/birthsvsdeaths-app/

![births vs. death app](assets/img/1-birthsvsdeaths.jpg)

--- .class #id 

# App Features

The app compares the births and deaths for a given country and region.

It features
* Country selection for all the worlds countries
* Selection of 33 different geographical or income regions
* Selection of the world as a special region
* Date range slider for specifying a time period of interest
* Two y axis modes for having a dynamic or fixed scaling
* Time series line plot comparing births and deaths

The app was realised using R and shinyapps from R Studio.

--- .class #id 

# Source Data 

The source data was taken from [World bank](http://data.worldbank.org) which is a repository containing data about development in countries around the globe.

In particular two data sets on crude births and deaths per 1000 population were used

[Crude births](http://data.worldbank.org/indicator/SP.DYN.CBRT.IN)   
[Crude deaths](http://data.worldbank.org/indicator/SP.DYN.CDRT.IN)

# References

[shinyapps.io](https://www.shinyapps.io)  
[R](http://www.r-project.org/)  
[R Studio](http://www.rstudio.com/)  
[World bank](http://data.worldbank.org)
