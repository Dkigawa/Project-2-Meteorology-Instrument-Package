# Project-2-Meteorology-Instrument-Package
Project 2: Meteorology 
Link to Final code: https://raw.githubusercontent.com/Dkigawa/Project-2-Meteorology-Instrument-Package/master/Project%202%20Meterology%20Instrument%20-checkpoint.ipynb

Link to code done by the due date (old version): https://raw.githubusercontent.com/Dkigawa/Project-2-Meteorology-Instrument-Package/master/Project%202%20Meterology%20Instrument%20-checkpoint.ipynb

Link to Repository: https://github.com/Dkigawa/Project-2-Meteorology-Instrument-Package 

Unsure how to display Photos in read me, Look in report in repository for easier to read report

Problem Statement:
Predicting the weather is an important science for modern society. One way to predict and stud the method is to compare different meteorological parameters by measuring parameters at different locations in the ocean. We took measurements from two mooring platforms, referenced from here on as the Oregon Shelf Surface Mooring and Oregon Offshore Surface Mooring. With data measured we can see the correlation between the two stations and see if data measured from one station can help predict what will happen at the next. 

Results:
To help display the meteorological information for each site I added different colors to help visualize what the weather was like during the time. As described in the text above the figure, it helps one understand how the weather changes over the year. 
Figure 1: Meteorological data for Shelf Surface Mooring station 
 
Figure 2: Meteorological data for Offshore Surface Mooring station
 

These figrues summerize each station’s data well, however it may be difficult to compare the two and see how they are related. To do that we focus on each type of data seperately, first comparing the wind speed between the locations. 
For the wind data the correlation was .73 with a 0 day lag. .73 suggests a strong correlation between the two. Correlation values can range for 1 to -1, where negative values mean the data sets act oppisitely to eachotehr. With .73 I consider evidnce enough to suggest strong correlation beween the wind speeds at both locations. Looking at the second graph of figure 3, most of the data is located at 0 and there is not a a clear pattern to  suggest a different relation between the data. 
max correlation is at lag 0
Lag in Days: 0
max correlation is 0.7334541198906394
The x-axis with 2001 points corresponds to all of the index values in the cross-correlation set








Figure 3: Correlation graph for Wind Speed
 
While there is strong evidence suggesting a strong correlation beweeen the wind speeds of each point, the same cannot be said for the proecipitation. With a correlation of .34, lesss than half the value for wind speed, suggest a far weaker correlation between the two satations for precipitation. It also has a 62050 lag in days, which is ridiculous taking in to account that this data was only measured for 1 year. Likely due to the lack of any real correlation between the two stations. A possible source of error is the focus on precipitation instead of rain rate. Other classmates were able to measure rain rate directly, however looking at the devices I was unable to obtain this data. It is possible that the measurement device for the precipitation works different than expected and I may be interpeting the values incorrectly. With the data I have, it suggest no real correlatino between precipitation between the two stations. 
max correlation is at lag 340
Lag in Days: 62050
max correlation is 0.3467482951414264
The x-axis with 2001 points corresponds to all of the index values in the cross-correlation set
Figure 4: Correlation graph for Wind speed
 
 Lastly for a simpler visualization of the data, the precipitation and wind speed was average for each month, allowing for a less “busy” graph. It re illistrates the correlation data in a simpler fashion, looking at both wind speeds, which earlier had a high correlation, the lines follow the same general trend, rising and falling at similair locations, only differing signifigantly in December. Whereas average precipitation for each location differ greatly, for example in Febuary, the Shelf station had it’s highest rain average, where conversly the offshore location had it’s lowest. If this trend continued it would have suggest a negative correlation, where they act in oppisite, however in the next month they both rise and fall at similar times, removing the possibility of a negative correlation. 
 
Overall, the time lag of 0 days for the wind speed suggests that they experience the same windstorms at both locations throughout the year. This makes sense because wind patterns can large enough to cross entire states easily, and since both are relatively close comparing to the size of the state, they likely are in the same system. Where the lack of correlation for the precipitation can be explained by how rainstorms can be more localized. Rainstorms can form from a variety of factors, and can change on a daily basis. 
The month with the highest amount of rain is February and June for the shelf (near the shore) location. For the Offshore location, November experience the higher amount of rain. The lowest rain amount for the shelf location was in December, for the offshore location the lowest rain amount was also in December. Suggesting that while stormy weather may be inconsistent between locations, when the weather gets drier both locations experience it similarly.
 The two highest average wind speeds for the Shelf station was in February and November, the Offshore location also had its highest average wind speeds during these months as well. This supports that there is a strong correlation between wind speeds of both locations. 
