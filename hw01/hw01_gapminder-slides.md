---
title: "Gapminder Exploration"
author: "Erika Luna"
date: "16/09/2019"
output: 
  ioslides_presentation:
    keep_md: true
---



# Exploring Gapminder dataset using R Markdown




## The Gapminder dataset is available in R. Below is a summary of the data: 

```
##         country        continent        year         lifeExp     
##  Afghanistan:  12   Africa  :624   Min.   :1952   Min.   :23.60  
##  Albania    :  12   Americas:300   1st Qu.:1966   1st Qu.:48.20  
##  Algeria    :  12   Asia    :396   Median :1980   Median :60.71  
##  Angola     :  12   Europe  :360   Mean   :1980   Mean   :59.47  
##  Argentina  :  12   Oceania : 24   3rd Qu.:1993   3rd Qu.:70.85  
##  Australia  :  12                  Max.   :2007   Max.   :82.60  
##  (Other)    :1632                                                
##       pop              gdpPercap       
##  Min.   :6.001e+04   Min.   :   241.2  
##  1st Qu.:2.794e+06   1st Qu.:  1202.1  
##  Median :7.024e+06   Median :  3531.8  
##  Mean   :2.960e+07   Mean   :  7215.3  
##  3rd Qu.:1.959e+07   3rd Qu.:  9325.5  
##  Max.   :1.319e+09   Max.   :113523.1  
## 
```

## The Gapminder data set has 6 variables:

```
## [1] "country"   "continent" "year"
```

```
## [1] "lifeExp"   "pop"       "gdpPercap"
```

## Gapminder encompasses 55 years of data, from 1952 to 2007. 

```
## [1] 1952 2007
```

## The following plot shows the population in each continent:
![](hw01_gapminder-slides_files/figure-html/gapminder_plot-1.png)<!-- -->
