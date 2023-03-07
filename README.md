# toyota_cars
This is a notebook which aims to predict the price of a Toyota car using decision trees, Random forrest and Gradient boosting

In this problem, we need to develop predictive model to predict "Price" for a Toyota corolla based on its features. The features provided in the dataset all characteristics of the car. The feature names are self-descriptives:

Id
Model
Price
Age_08_04
Mfg_Month
Mfg_Year
KM
Fuel_Type
HP
Met_Color
Color
Automatic
CC
Doors
Cylinders
Gears
Quarterly_Tax
Weight
Mfr_Guarantee
BOVAG_Guarantee
Guarantee_Period
ABS
Airbag_1
Airbag_2
Airco
Automatic_airco
Boardcomputer
CD_Player
Central_Lock
Powered_Windows
Power_Steering
Radio
Mistlamps
Sport_Model
Backseat_Divider
Metallic_Rim
Radio_cassette
Parking_Assistant
Tow_Bar

We use auto Viz package to help us understand the varibales to work with 

We identify categorical columns and treat them by passing them through a sklearn One hot encoder.

In the end, we calculate lowest RMSE of each model to help us get an idea of how to proceed further with a decision.
