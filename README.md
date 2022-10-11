# practical_app_5

In this repository we examine the relationships between driver attributes and wether they will accept coupons offered to them while they drive.

We first explore coupons for a bar. To do this we isolate a table that consists of only coupons offered specifically for a bar. We take this table and explore the characteristics of different features by subseting the data according to varying requirements such as Age, number of passenders, incomem, etc. The metric used for these explorations is the rate of acceptance of each subset of the data. This is calculated with: $\mathrm{acceptance\ rate}=\frac{\mathrm{acceptances}}{\mathrm{total\ number\ of\ coupons}}$

With regards to the bar data, the overall most usefull feature for predicting the acceptance rate seemed to be the frequency with which the driver went to bars each month. In the notebook a variety of specific conditions are explored with varying acceptance rates.

Once the bar data is explored we move on to examine coupons for coffee houses. This is done in a similar fashion as the bar data. First a table of only coupons for coffee houses is isolated, then various features of this table are explored with respect to acceptance rate of the driver. The results of this are plotted in the notebook. 

These aforementioned plots and underlying data show that age, destination of the driver, time of day, and passengers in the car all play a significant part of determining the likely hood of the driver accepting a coupon. The specific ways in which these features affect acceptance rate is shown in the notebook.

