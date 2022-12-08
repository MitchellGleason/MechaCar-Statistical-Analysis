# MechaCar Statistical Analysis

# Overview
The purpose of this project is to use R to analyze MechaCar data to identify key metrics and trends that will help the manufacturing team make decisions about the production process. The data set contains information about the MechaCar prototypes, including vehicle length, weight, spoiler angle, drivetrain, and ground clearance. The data set also contains information about the miles per gallon (MPG) of each prototype. The MechaCar team is interested in understanding how the different variables affect the MPG of the MechaCar prototypes.

## Linear Regression to Predict MPG
![Figure 1](Figures/Fig1.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Two variables in this dataset provide a non-random amount of variance: vehicle length and ground clearance. The p-value for each of these variables is less than 0.05, which indicates that they do provide some amount of corelation to the mpg values in the dataset. The p-value of vehicle weight, spoiler angle, and AWD are significantly further from 0.05, which indicates that they do not provide a corelation to the mpg values in the dataset.

### Is the slope of the linear model considered to be zero? Why or why not?

The p-value of the linear model is 5.35e-11, which is significantly less than 0.05. This indicates that the slope of the linear model is not zero. This means that the linear model does provide corelation to the mpg values in the dataset.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

This linear model predicts the mpg of MechCar prototypes relatively effectively. The R-squared value is 0.7149, which indicates that 71.49% of the mpg values can be predicted by the linear model. This is a relatively high R-squared value, which indicates that the linear model is a good fit for the data.