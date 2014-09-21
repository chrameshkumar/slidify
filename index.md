---
title       : assignment
subtitle    : one
author      : self
job         : consulting
framework   : revealjs     
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
 
## Data exploration - introduction

1. Assignment to analyze and screen monthly raw data
2. Data screening is critical activity
3. Huge amount is spend in big data analysis for data screening
3. Significant as critical business decisions are made on the basis of data analysis
4. Uses pollution data set in R as test case to explain the process
5. Explores shiny to develop interactive dynamic web application
6. Can be modified for analyzing any raw data 
 

--- .class #id 
## Scope of work
1. Review the transactions data to identify errors
    * NA values
    * Inconsistent values
    * Missing data
2. Provides following to felicitate this review
    * Month for data review can be dynamically selected
    * Summary of the data for selected month displayed
    * Graph for selected month and selected variable displayed to visualize inconsistency
    * Selected number of records displayed to identify actual error 

--- .class #id
## Input data
* uses ‘airquality’ in R data set as basis for explaining the process
* Data set contains five month data - May to September
* Number of observations 153 - one observation per day
* NA records are retained, as cleaning data with correct values is the objective of this exercise
* First five observations displayed below to explain the fields


```
##   Ozone Solar.R Wind Temp Month Day
## 1    41     190  7.4   67     5   1
## 2    36     118  8.0   72     5   2
## 3    12     149 12.6   74     5   3
## 4    18     313 11.5   62     5   4
## 5    NA      NA 14.3   56     5   5
```

--- .class #id 
## Process details 
1. On opening in a browser
  * Displays part of side panel in the left
  * Displays default summary data for May and ozone graph for May
  
2. Side panel in left allows dynamically to
  * Change the month to display data through a pull down menu
  * Change the graph variable by set of radio buttons
  * Displays check books for viewing records

---.class #id 

## Process details ....contd,,,
3.  Clicking on the check box triggers the following:
  * Five observations for the seleced month is displayed below the graph
  * Above the graph number of records displayed is shown
  * Slider bar appears in the left panel that allows selection of records from 1 to 31
  * Records shown dynamically changes based on the slide bar value
  * clearing the checkbox clears everything shown on checking 

---.class #id
## Summary

  * Shiny offers excellent framework for funtional area specialist to develop thier own web pages
  * This assignment give a framework for creating error free data
  * Graphical interfact privided isual inspection to identofy data error 
  * Observations can also be displayed to pin point error to initiiate corrective action
  * End result is creation of error free observation that can be pushed to the final data set
  
  



