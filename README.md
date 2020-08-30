# PyBer_Analysis

#Overview:

#The exercise, for the class, allowed us an intro to graphs for python, similar to the initial kickstarter process. It served to show us how graphs can be made, and which ones
are most useful for specific purposes. Using a line graph would be best for following multiple pieces of data over time, for example, whereas a bar graph may be more appropriate
for a moment in time. 

#within the scenario, the goal is to look at the rides across different times and places, both as constant statistics and as a graph over time, and determine what trends, if any,
can be noticed to increase profits. Both are needed, as the chart over time shows us if there are any outlying dates, which can be used advantageously, while the larger summation
of datapoints can show us what's true on an "average" day, and plan accordingly.

#results:

#within the results, there appears to be an inverse relationship between the frequency of rides/the amount of drivers, and the cost of the rides. In the cities, there are 
significantly more drivers and rides being given. Although there's increased demand, and therefore a higher gross sum, the total fare per ride is significantly lower, most likely 
because drivers charging too much in the city will be refused in favor of cheaper drivers. In rural communities, there's less overall demand for rides, but also fewer drivers, 
making passengers less able to refuse drivers in favor of others. Suburban communities, much like how they are a hybrid of urban and rural communities, fall in the middle of these
trends. The chart pyber_dataframe.png shows these points best.

#the chart over time, PyBer_fare_summary.png, demonstrates that the trends tend to hold over time, and while events don't impact every community equally, they do trend in the same
directions. Looking at the time around february 20th, for example, shows all three trend up, possibly in response to a holiday or event all three would celebrate like president's 
day. In these cases, a combination of more people needing rides and drivers valuing this time more (it could be a holiday, but they are instead working, making it likely they're 
seeking extra compensation) tend to increase the fares. 

#Recommendations:

# though obvious, the biggest takeaway is adding drivers will increase the total amount of rides given, but will lower the cost of rides. If the rural communities were suddenly 
given some of the city drivers, for example, the total rates may go down as there's more competition, but the affordabilty may encourage more in rural communities to want rides.
likewise, the city prices may go up from fewer drivers, encouraging those who don't want to pay to take other transportation.Though it's difficult to say which way they should 
trend from this data alone, it's important to keep this balance in mind should there be too many/few in one area.

# Another big takeaway is to anticipate when people will need rides, and prepare accordingly. The big urban spike in March, for example, is likely due to Saint Patrick's day.
While people likely drink and cannot drive in every community that day, it appears more likely people in urban areas cannot rely on a DD or friend to drive them home, or walking is
not a viable option. If the amount of drivers is either increased or decreased according to the logic above, the holiday could become more profitable. 

#on a note of flexibility, it's likely urban city prices are lower not only for internal competition, but external as well. larger cities have the capacity to house subways,
non-rideshare taxi services, and other methods of transportation, whereas rural and suburban areas cannot house this to a similar degree. therefore, even if you remove or add
drivers, you will not have as much influence in an urban city as you will other places. Therefore, things implemented identically may not have the same impact everywhere, and
any big plans must be made realizing urban areas will either need more force to have the same effect, or an equal force will give less impact.
