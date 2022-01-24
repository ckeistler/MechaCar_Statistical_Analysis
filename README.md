# MechaCar_Statistical_Analysis



## Linear Regression to Predict MPG
![deliverable1A](https://user-images.githubusercontent.com/88443672/145734873-d1457400-5a82-4d9c-a284-81562e19bedb.png)
![deliverable1B](https://user-images.githubusercontent.com/88443672/145734876-f0ec7301-b7c1-4b00-a5cd-912f651bf050.png)

### Deliverable 1 Summary
      
- Q1: Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle length and ground clearance
      
- Q2: Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not consideredd to be zero.  

The R-squared value of 0.7149 says that ~71.5% of the variance of the dependent variable stems from the variables included.  The p-value of our linear regression  analysis is 5.35 x 10-11, which is much smaller than our assumed significance level of 0.05%, and the slope of our linear model is not zero.

- Q3: Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Effective might be a strong word in this case ... maybe "moderately-effective" is a better term.  An R-squared of 71.5% is a positive indicator for sure, but there is still plenty of room for error/variance that isn't accounted for in the model.  Adding additional factors could help increase the R-squared futher.
      
        
## Summary Statistics on Suspension Coils
![d2A](https://user-images.githubusercontent.com/88443672/145734979-e29556bc-d721-4a73-8029-56c839505d85.png)

![d2B](https://user-images.githubusercontent.com/88443672/145736705-73d2de9b-b9ed-4fcc-9c52-b8661c76f825.png)

![d3C](https://user-images.githubusercontent.com/88443672/150871513-39a49a1d-924f-4d89-81ac-2aeb65cb2b2b.png)

#### Q1: The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
      The variance, inclusive of all manufacturing lots, does not exceed 100 pounds per square inch.  As a whole, the design specifications are met.  That said, Lot 3 variance was 170.29 psi, while Lots 1 and 2 were less than 10.  Lot 3 does not meet the mentioned design specification.
      
## T-Tests on Suspension Coils
![d3A](https://user-images.githubusercontent.com/88443672/150873484-108bef0a-4f5e-4b58-aad8-44c9af5ae6e5.png)

![d3B](https://user-images.githubusercontent.com/88443672/150873493-de54e47d-f27b-4a9d-9ffc-d7f72e658288.png)

![d3C](https://user-images.githubusercontent.com/88443672/150873509-5692eb2f-6edb-4fb3-b6d3-d26d417fbe4c.png)

#### Q1: Briefly summarize your interpretation and findings for the t-test results

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
