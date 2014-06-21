---
title       : CrowdSize
subtitle    : a tool for estimating crowd sizes
author      : Bryn R Williams
job         : Coursera project 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}


---
## The Wisdom of Crowds


Introducing a tool that will help journalists and others around the world
to more easily estimate the size of a crowd

In an age where people are increasingly taking to the streets to display their
dissatisfaction with their political leadership, the numbers of those
participating becomes a significant indicator of the level of protest.



---
## CrowdSize


News organisations have a responsibility to accurately judge those numbers
to tell the whole story, and often it is a matter of dispute. 

The authorities may claim one figure while the organisers claim another.

To this end I have designed CrowdSize, an application which will aid journalists in estimating the numbers of a crowd.


Using a simple algorithm, all you need to know is the width and length of whichever public space is occupied to determine the number of people that are taking part.

---
## The Algorithm


For any area, multiply length by width and divide by the space occupied by each person.
If we take that length=100m
                width=50m
            and space per person = 0.85m
                (how close people are standing to each other determines the space they take up)
Then


```r
100 * 50/0.85
```

```
## [1] 5882
```


So, in an area 100m by 50m, if people are occupying 85cm each (that's pretty tight packing)
then there will be something in the region of 5,882 of them.

---
## Crowd and Proud




Although CrowdSize still depends on users making a judgement of how tightly packed an area is, it allows them to play with those judgement's to come up with the most reasonable estimate.

---
## Loud, Crowd and Proud




I hope you will agree that CrowdSize marks a substantial contribution to easing the workload of crowd evaluators around the world, and providing more accurate estimates by which we can judge the strength of public feeling...or just figure out how many people are crowded around the Big screen in the Pub during a World Cup match.


