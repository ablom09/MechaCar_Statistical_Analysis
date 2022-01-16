# MechaCar_Statistical_Analysis

# Project Overview

In order to help out Jeremy and upper managements concerns about a new prototype vehicle, we have been tasked with compiling the production data for insights into vehicle performance. More specifically, metrics such as vehicle length, weight, amongst others will be analyzed to determine overall performance qualities and varying manufacturer lots. Following this review, we shall then lay out a statistical study comparing these various vehicle performances based on our findings. 

# Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/91284661/149682322-784e21e4-62e8-49bf-a934-a385f8543e10.png)

•	From our results, it can be observed that vehicle length and ground clearance provide non-random amounts of variance to our model. In other words, vehicle length and ground clearance certainly impact the MechaCar protype’s miles per gallon. Also, the vehicle weight, spoiler angle, and All Wheel Drive have p-values which suggest divergent random amounts of variance within our data.

•	Given our p-vlaue of 5.35e-11 being significantly smaller than our significance level of .05%, we can safely state reject our null hypothesis. This would also further indicate that the slope of our model is non-zero.

•	Furthermore, factoring in our r-squared value of .7149, (which suggests approximately 71% of our MPG predictions being determined by our model,) we can state the multiple regression model doesn’t predict MPG of the MechaCar protype efficiently.
