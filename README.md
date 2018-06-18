
<!-- README.md is generated from README.Rmd. Please edit that file -->
El uso del paquete es esclusivo para

``` r
library(resumeR)
```

    ## Loading required package: e1071

    ## Loading required package: car

    ## Loading required package: carData

``` r
x<-rnorm(25,2,3)
resume(x)
```

    ## [1] "You got Normal distribution."
    ## [1] "Warning: You have a low sample size (n<30)"
    ## [1] "You do not have outlier"

![](README_files/figure-markdown_github/unnamed-chunk-1-1.png)

resumeR\_uso\_paquete
=====================

The goal of resumeR\_uso\_paquete is to ...

What is special about using `README.Rmd` instead of just `README.md`? You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist    
#>  Min.   : 4.0   Min.   :  2  
#>  1st Qu.:12.0   1st Qu.: 26  
#>  Median :15.0   Median : 36  
#>  Mean   :15.4   Mean   : 43  
#>  3rd Qu.:19.0   3rd Qu.: 56  
#>  Max.   :25.0   Max.   :120
```

You'll still need to render `README.Rmd` regularly, to keep `README.md` up-to-date.

You can also embed plots, for example:

![](README_files/figure-markdown_github/pressure-1.png)

In that case, don't forget to commit and push the resulting figure files, so they display on GitHub!
