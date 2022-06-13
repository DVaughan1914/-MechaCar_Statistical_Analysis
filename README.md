# MechaCar_Statistical_Analysis

# Linear Regression to Predict MPG
 - Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and   vehicle_length.

- Is the slope of the linear model considered to be zero? Why or why not?

- Our slope is not zero just be looking at the p-value, which is less than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

- Our R-squared value is roughly 70%, which means roughly ~70% of the time the model will predict mpg values correctly. There are probably other factors that were    not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.

# Summary Statistics on Suspension Coils

-The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and Lot 2 are both within design specifications and have nearly the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

# T-Test on Suspension Coils
  - Lot 1 and Lot 3 the PSI values are not different from the population mean. However lot 2 the p-value is .607 which means there is evidence that the suspension coil is different from the population mean. All t-tests can be seen below:

# ALL LOTS:
<img width="570" alt="Suspension_PSI" src="https://user-images.githubusercontent.com/100040621/173267680-187a00d5-20dd-44e2-9fff-6b3a6eed693a.png">

<img width="552" alt="Lot_1" src="https://user-images.githubusercontent.com/100040621/173267701-b027eb72-d006-48ac-8952-b25846ca207e.png">

<img width="557" alt="Lot_2" src="https://user-images.githubusercontent.com/100040621/173267711-029f4c9e-d2a9-4034-aa44-0b7df91e022f.png">

<img width="561" alt="Lot_3" src="https://user-images.githubusercontent.com/100040621/173267717-58a2c7bd-2a27-431c-a8bf-1a4c8313c779.png">


# Design Study: MechaCar vs Competition

  - One feature that people are interested in when buying a car is how much horsepower the car has. I think horsepower, mpg and how large the engine is are 3 factors that go into consumer decision making. We can use our tests to see if our MechaCar is much different from the competiton. We can make a null hypothesis stating that it is not different from the competition and our Alternative would be the opposite. To do this we will need to use our t-test after collecting data from different types of competitor vehicles. Our t-test will be comparing the population of all types of competitor vehicles.



