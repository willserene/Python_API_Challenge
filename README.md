# Python API Challenge

This project entailed the use of API calls and python script for the acquisition, manipulation, and visualization of weather and map data in jupyter notebooks. 

Although difficult, scripting the "for loops" and "try and except clauses" for the API calls, was incredibly rewarding to finally nail down. 

![ForLoop_TryExcept_openweather](https://user-images.githubusercontent.com/79114121/115125854-31837700-9f88-11eb-85b1-e71ea400d795.png)

![ForLoop_TryExcept_gmaps](https://user-images.githubusercontent.com/79114121/115125857-3516fe00-9f88-11eb-9142-a07cef13ac24.png)

The latitude of each city was plotted against four respective variables including: max temp, humidity, cloudiness, and windspeed. Cities were grouped by northern and southern hemisphere, after which linear regressions were performed to analyze the relationship between their latitudes and each of the four variables.  

The analyses on latitude vs maximum temperature reflected a strong and predictable relationship. This is captured well in the scatter plot below, and supported in the subsequent regressions, specifically with the correlation coefficients of -0.88 and 0.7 for the northern and southern hemispheres, respectively. 

![latvstemp](https://user-images.githubusercontent.com/79114121/115125867-4102c000-9f88-11eb-9e85-aed95f7205a5.png)

![north_latvstemp_regression](https://user-images.githubusercontent.com/79114121/115125873-4a8c2800-9f88-11eb-9aa5-b1098df1240a.png)

![south_latvstemp_regression](https://user-images.githubusercontent.com/79114121/115125875-4cee8200-9f88-11eb-88a4-6dedd1a862c9.png)

Analyses on the remaining variables reflected weaker relationships with latitude, as measured by their correlation coefficients, although the overall trends made intuitive sense. For example, humidity and cloudiness in the southern hemisphere had correlation coefficients of 0.31 and 0.33. The closer a city is to the equator is similarly and positively correlated with its cloudiness and humidity %.

![south_latvshumidity_regression](https://user-images.githubusercontent.com/79114121/115125881-5c6dcb00-9f88-11eb-9fa5-b1a9ab14e84e.png)

![south_latvsclouds_regression](https://user-images.githubusercontent.com/79114121/115125885-6394d900-9f88-11eb-90ac-68f8e354dd89.png)

Cloudiness % in the northern hemisphere however showed almost no relationship at all with latitude. This is captured in the below plot, with the regression yielding a correlation coefficient of 0.07. 

![north_latvsclouds_regression](https://user-images.githubusercontent.com/79114121/115125892-74454f00-9f88-11eb-962d-85be5e67a674.png)



