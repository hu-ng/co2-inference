# Bayesian Model of CO2 measurements from 1958 to now.

## Description
This project models the data from the [Scripps CO2 program](https://scrippsco2.ucsd.edu/data/atmospheric_co2/mlo.html), which has been updated weekly since 1958. The goal is to use the model to predict when CO2 levels will reach 450 ppm (parts per million), which is considered to be [highly dangerous](https://sustainabilityadvantage.com/2014/01/07/co2-why-450-ppm-is-dangerous-and-350-ppm-is-safe/) for the environment.

## Model
You can read more about my modelling process in the PDF included in the repo. Here's a visualization of my model:
![model](https://github.com/hu-ng/co2-inference/blob/master/img/factor%20graph.png)


## Results

The original data looks like so:
![original-data](https://github.com/hu-ng/co2-inference/blob/master/img/data.png)

And here the prediction from my model, up until the year 2060:
![result](https://github.com/hu-ng/co2-inference/blob/master/img/prediction%20full.png)

A closer look reveals that the 450 ppm level will most likely be reached by *2034*:
![zoomed-result](https://github.com/hu-ng/co2-inference/blob/master/img/prediction%20zoomed.png)
