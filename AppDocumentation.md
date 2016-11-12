## App Documentation

This Shiny web application is meant as data analysis on the USCrudes data within the Applied Econometrics 
Package (AER) in R. This dataset contains Cross-sectional data originating from 99 US oil field postings states.
It consists of a dataframe which contains 99 observations on 3 variables, containing USD oil price per barrel(USCrudes), degree 
of API(gravity) and sulphur in %(sulphur).
In the App it is possible to do various two-dimensional regressions. The following choices can be made:
- Linear: This is the ordinary linear regression
- Loess: Smooth non-parametric regression
- Lowess: A generalized version of the Loess, smooth non-parametric regression
- Smooth-spline: A smooth regression that uses splines

One can select two x-values, being the degree of API (gravity) and the suplhur rate (sulphur).
Also one can select how many datapoints one wants to use.
