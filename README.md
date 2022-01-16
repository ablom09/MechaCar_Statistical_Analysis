# MechaCar_Statistical_Analysis

# Project Overview

In order to help out Jeremy and upper managements concerns about a new prototype vehicle, we have been tasked with compiling the production data for insights into vehicle performance. More specifically, metrics such as vehicle length, weight, amongst others will be analyzed to determine overall performance qualities and varying manufacturer lots. Following this review, we shall then lay out a statistical study comparing these various vehicle performances based on our findings. 

# Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/91284661/149682322-784e21e4-62e8-49bf-a934-a385f8543e10.png)

•	From our results, it can be observed that vehicle length and ground clearance provide non-random amounts of variance to our model. In other words, vehicle length and ground clearance certainly impact the MechaCar protype’s miles per gallon. Also, the vehicle weight, spoiler angle, and All Wheel Drive have p-values which suggest divergent random amounts of variance within our data.

•	Given our p-vlaue of 5.35e-11 being significantly smaller than our significance level of .05%, we can safely state reject our null hypothesis. This would also further indicate that the slope of our model is non-zero.

•	Furthermore, factoring in our r-squared value of .7149, (which suggests approximately 71% of our MPG predictions being determined by our model,) we can state the multiple regression model doesn’t predict MPG of the MechaCar protype efficiently.

# Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/91284661/149682522-ea3fc505-21ce-4300-b013-57ce35351d43.png)

![image](https://user-images.githubusercontent.com/91284661/149682528-245f73f5-55e3-4459-9d24-ea335a19a117.png)

In observing the variance over our dataset, we can determine that the current manufacturing data meets the 100 pounds per square inch variance limitation. Still, one looking over the three lots individually, we can spot that lot number 3 shows higher overall variance. Because of these findings, it is therefore reasonable to assume the possibility that lot number 3 doesn’t meet the necessary requirements involving suspension coils.

# T-Test on Suspension Coils

![image](https://user-images.githubusercontent.com/91284661/149682568-15fc5bf3-eaf3-45ec-a900-a6212d14aba7.png)

# T-Test on Entire Lot

At a significance level of .05, we fail to reject our null hypothesis based on our resulting p-value of .06028. From this, we cannot reject the fact that the sample mean may be equivalent to the true population mean.

![image](https://user-images.githubusercontent.com/91284661/149682710-90352d74-d8e0-4dad-b187-884aaded735f.png)

# T-Test on Three Smaller Lots

Lot 1: At a significance level of .05, we fail to reject our null hypothesis. 

Lot 2: At a signifance level of .05, we would fail to reject our null hypothesis.

Lot 3: At a significance level of .05, we would reject our null hypothesis. When observing the mean of our sample, being smaller than our previous two lots, this makes sense. Also unlike our previous two lots, the confidence interval for Lot 3 wouldn’t include the predicted population mean.
