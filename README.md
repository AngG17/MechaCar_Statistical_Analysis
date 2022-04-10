# MechaCar_Statistical_Analysis

## Overview

AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress.  This analysis will review production data for insights that will help the manufacturing team.

## Results

### Linear Regression to Predict MPG

![Deliverable 1](https://user-images.githubusercontent.com/95720986/161442840-565e41c7-bc62-483f-aae1-ed453ce1cc00.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle length
- Ground clearance

Is the slope of the linear model considered to be zero? Why or why not?
- The slope of the linear model is not zero as shown by the p-value of 5.35x10<sup>-11</sup> and the null hypothesis must be rejected.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- This model does predict the MPG of the prototype as shown with a R-squared value of 0.7149.  This model is 71% accurate, although it could be better.

### Summary Statistics on Suspension Coils

![total_summary](https://user-images.githubusercontent.com/95720986/161442537-0bf14537-33b7-4627-8d33-bd6c8ca03a22.png)

![lot_summary](https://user-images.githubusercontent.com/95720986/161442544-ee8f9b12-cd8d-499c-9298-be4f77a72499.png)

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The overall variance is under 100 psi and meets specifications, but Lot 3 is well over an acceptable threshold at 170.29.

### T-Tests on Suspension Coils

All lots T-test:

![one sample t-test](https://user-images.githubusercontent.com/95720986/161442669-3868ddb8-e252-4745-a4d9-3a193dea8226.png)

- There is no statistical difference from the population mean for all lots and the p-value is not low enough to reject the null hypothesis.


Lot 1 T-test:

![Lot 1](https://user-images.githubusercontent.com/95720986/162633015-b91c98e7-3f03-4efc-8151-a019adb026b5.png)

- There is no statistical difference from the population mean for Lot 1 and the p-value is not low enough to reject the null hypothesis.

Lot 2 T-test:

![Lot 2](https://user-images.githubusercontent.com/95720986/162633024-7dfcd200-864e-4906-8892-504cb97c0560.png)

- There is no statistical difference from the population mean for Lot 2 and the p-value is not low enough to reject the null hypothesis.

Lot 3 T-test:

![Lot 3](https://user-images.githubusercontent.com/95720986/162633034-09bd6195-a91f-4c86-b1b4-4aafbc9bf299.png)

- There is a slight statistical difference from the population mean for Lot 3 and the p-value is low enough to reject the null hypothesis.  This lot may need to be discarded or re-evaluated.


## Study Design: MechaCar vs Competition

