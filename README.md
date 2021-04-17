# python-api-challenge

This challenge entailed the use of API calls and python script for the acquisition, manipulation, and visualization of weather and map data in jupyter notebooks. 

Although difficult, scripting the "for loops" and "try and except clauses" for the API calls, was incredibly rewarding to finally nail down. 

Insert screenshots here.

The latitude of each city was plotted against four respective variables including: max temp, humidity, cloudiness, and windspeed. Cities were grouped by northern and southern hemisphere, after which linear regressions were performed to analyze the relationship between their latitudes and each of the four variables.  

The analyses on latitude vs maximum temperature reflected a strong and predictable relationship. This is captured well in the scatter plot below, and supported in the subsequent regressions, specifically with the correlation coefficients of -0.88 and 0.7 for the northern and southern hemispheres, respectively. 

Insert temp scatter plot

Insert north lin regress temp

Insert south lin regress temp

Analyses on the remaining variables reflected weaker relationships with latitude, as measured by their correlation coefficients, although the overall trends made intuitive sense. For example, humidity and cloudiness in the southern hemisphere had correlation coefficients of 0.31 and 0.33. The closer a city is to the equator is similarly and positively correlated with its cloudiness and humidity %.

Insert south humid and cloud regress plots here

Cloudiness % in the northern hemisphere however showed almost no relationship at all with latitude. This is captured in the below plot, with the regression yielding a correlation coefficient of 0.07. 

Insert north cloud lin regress plot here


