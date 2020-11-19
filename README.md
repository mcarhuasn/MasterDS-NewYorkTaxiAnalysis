# New-York-Taxi-Analysis

## Problem definition
Predict the average money spent on taxi rides for each region of New York per given day and hour.

This problem is a supervised regression problem. Supervised because we have the actual value of the value we’re trying to predict and regression because what we’re trying to predict is a continuous variable (as opposed to categorical).

## Data problems I fixed

![Negative and zero values graph](/images/Negative_and_zero_values_graph.png)

*Negative total_amount values:* removed them since they are likely faulty data points and there weren’t many of them
*Zero values for total_amount:* Same with negative values. Zero values are removed.


![Graph showing the too high values](/images/too_high_values_graph.png)
