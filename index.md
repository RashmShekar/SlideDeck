---
title       : Heart Attack Prediction
subtitle    : Predits the risk of heart attack based on cholesterol level
author      : Coursera Student
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Slide 2
Prediction Algorithm is

```r
heartAttack <- function(cholesterol) {
    if (cholesterol < 200) 
        "no risk of heart attack" else (if (cholesterol > 199 & cholesterol < 240) 
        "Borderline high risk of heart attack" else "high risk of heart attack")
}
```

--- .class #id 

## Slide 3
Cholesterol level of 199 mg/dl results in a prediction of 

```
## [1] "no risk of heart attack"
```



--- .class #id 

## Slide 4
Cholesterol level of 230 mg/dl results in a prediction of 

```
## [1] "Borderline high risk of heart attack"
```


--- .class #id 

## Slide 5
Cholesterol level of 250 mg/dl results in a prediction of 

```
## [1] "high risk of heart attack"
```

