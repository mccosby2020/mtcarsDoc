---
title       : Motor Trend Cars Modeler Documentation
subtitle    : 
author      : Vincent Amedekah
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction
Motor Trend Cars Modeler Application is for adding variables avaiable in the mtcars data to a linear regression model for the mpg based on the transmission type(manual or automatic)
Application is web based and requires internet and web browser to access.
The application is hosted on the shiny server at https://mccosby2020.shinyapps.io/mtcarAnalyzer/ .

A look at the mtcar data 


```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
```

--- .

## Application Home Page
Application has a sidebar on the left and  main area to the right.<br>
side bar has a check box of variables in the mtcar data that can be added to model.<br>
Side bar has a submit button at the bottom which must be clicked to cause changes to model.<br>
Four plots on model is displayed in the main area.<br>
A summary statistics of the model is displayed showing details of new model.<br>
Based on this information user can decide which model fits better with the mtcars data

---

## Adding predictor variables
Users can add variables to the linear model to make changes.<br>
To add a variable to the linear model, select the variables from the side bar.<br>
Click the submit button and a new model detail gets generated in the main area.<br>
A plot and summary of the model is shown in the main area.<br>
A summary statistic is shown in the main area and the model formula is displayed

---

## Sample output
adding hp and wt variables from the side bar will produce plots below 
![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)
---
