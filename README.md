# MechaCar_Statistical_Analysis
MOD 15 Challenge
# Background
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on the data analytics team to review the production data for insights that may help the manufacturing team.

In this projec the data analytics team will do the following:

  * Perform multiple linear regression analysis to identify which variables in the dataset predict the miles per gallon (MPG) of MechaCar prototypes
  * Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
  * Run t-tests to determine if the manufacturing lots are statistically different from the mean population
  * Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. 

## Hypothesis:

### H0: (null) States that dimensions of the vehicle (length, width, and weight), the ground clearance, drive train (AWD) and the spoiler angle will not be a statistically significant predictor of MPG.

### HA: States that dimensions of the vehicle (length, width, and weight), the ground clearance, drive train (AWD) and the spoiler angle is a statistically significant predictor of MPG.

## Linear Regression to Predict MPG
The dataset contains the variables likly to effect MPG. The dimensions of the vehicle (length, width, and weight), the ground clearance, drive train (AWD) and the spoiler angle. According the the model there is statistical significance that the variable will present consistent variances. The vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset. The p-Value for the model is **5.35e-11**  rejecting the null hypothsis. The r-squared value of **.7149** defines this model as reliable

![Statistical Summary 1a ](https://github.com/JBtallgrass/MechaCar_Statistical_Analysis/blob/main/Images/Deliverable_1a.png)

Below is the Statistical summary if the following independent variables (less signigficant) were removed.

![Statistical Summary 1b ](https://github.com/JBtallgrass/MechaCar_Statistical_Analysis/blob/main/Images/Deliverable_1b.png)

 
## Create Visualizations for the Trip Analysis

![Statistical Summary](https://github.com/JBtallgrass/MechaCar_Statistical_Analysis/blob/main/Images/Rplot01.png)

![Statistical Summary](https://github.com/JBtallgrass/MechaCar_Statistical_Analysis/blob/main/Images/Total_summary.png)

![Statistical Summary](https://github.com/JBtallgrass/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png)

## T-Tests on Suspension Coils
![Statistical Summary](https://github.com/JBtallgrass/MechaCar_Statistical_Analysis/blob/main/Images/T-tests.png)


## Design a Study Comparing the MechaCar to the Competition

### The statistical study design framework must include the following items: 

 1. A null hypothesis or an alternative hypothesis is described
 2. A metric that is measured through recognized measurements
 3. Must be repeatable- given similar circumstances
 4. have a statistical test applied

To be of use to the manufactor the MechCar comparitive analysis will include similar cars from variuos manufactors. The vehicles must be like-types so as to present an objective analysis.  Once determined each model must be evaluated within the identical features. The following features are potential catagories for analysis:

Value: Dependent Variable

  - Safety Feature Rating: Independent Variable
  - Engine (Electric, Hybrid, Gasoline / Conventional): Independent Variable
  - Maintenance costs: Independent Variable
  - Malfunctions (time in repair): Independent Variable

### Hypothesis: Null and Alternative
After determining the evaluation criteria and metrics the two hypotheses should read as follows:
   **Null Hypothesis**  (Ho): MechaCar is priced correctly based on its performance of key factors for its genre.
   **Alternative Hypothesis** (Ha): MechaCar is NOT priced correctly based on performance of key factors for its genre.

### Statistical Tests
A multiple linear regression could determine the highest correlation/predictability with value (dependent variable)



