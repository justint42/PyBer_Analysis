# PyBer Analysis

## Overview

PyBer, a popular, critcally-accalimed ride-sharing service, has tasked the user with performing an exploratory analysis to to analyze the differences of data amongst city types. Decision makers will use this data to decide their next plan of action. Technically, the user will learn the intricacies of MatPlotlib in conjuction with Pandas to visualize data. 


## Results 

<img width="473" alt="PyBer_chart" src="https://user-images.githubusercontent.com/106895220/178657970-bd180fa5-d7ee-41b8-a0a3-29a735c4c154.png">

![Pyber_fare_summary](https://user-images.githubusercontent.com/106895220/178644312-64da4670-12d5-44d6-9d2e-fde92fe4e917.png)

Overlying summary statistics per major factors shows a disparity the average fares and city types (expected, though significant). City types of higher populations experience lower fare rates than that of rural. Low populations in rural communities facilitate a need for greater charges; there are not as many drivers and riders in smaller communities. From this we surmise:

- Ride demand (and arguably, "need" for drivers") increases as community population increases.
- There is a point in population size where fares per drivers increase as fares per ride decreases.
- Surburban communities act as a 'middle ground' when looking at extremes.
- Fare revenue is mostly determined by population volume.

While city type is a primary driver of fare rates, we must examine other reasons for city type fare disparities. What can be done to mitigate  high fare costs in rural communitites? Can urban drivers get paid more? The statistics of the specific cities examined may shed insight on what can be done. 

## Summary

The high fare rate from drivers in rural and suburban markets implies that more drivers can be hired to meet demand. This solution may not solve this discrepancy problem; other factors are in play. To construct a solution that resolves in long-term positive value, we must create a system that pays attention to positive responses to drivers. How can we create a system that is the same visually across all city types? Outside of the economic outputs of our variables, we may have to look to more "localized" variables that are unique to each city type. If different city types result in different or disparate values, then there must be a way to capitalize on them without sacrificing short-term gain.
