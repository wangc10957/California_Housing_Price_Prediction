# California_Housing_Price_Prediction
## Data Type
The California housing Price data set can be found on Kaggle at https://www.kaggle.com/camnugent/california-housing-prices. This data slips houses into groups.  From the housing groups we are given several variables. 
The data has a single categorical variable which is ocean proximity and continuous varaibles logitude, latitude, median housing age, total number of rooms (for each area), total number of bedrooms (for each area), population (in that area), number of households (number of houses within each area), median income (in $10,000), and median house value (in dollars).

The data will be used to predict the median housing value.

## Problem Type
The prediction of median housing value is calculated using regression and deep learning with R.

## Proposed Network
Since this problem is regression we will use feed forward.  To improve the network we will explore using random dropout for the epochs and changing epoch size.  Also since the data set itself is so large we will take a random sample of size 1000 for training and 500 for testing.  We will compare the results for each tweak we make to fine the best one.
