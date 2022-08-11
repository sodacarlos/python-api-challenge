# WeatherPy

## Scatter Plots code analysis explanation:

### Temperature (C) vs. Latitude:

This scatter plot demonstrates how the maximum temperature changes as you reach (or move away) the equator (Latitude of 0). In the southern hemisphere, the maximum temperature starts to fall as you travel further south. Further north in the northern hemisphere, the maximum temperature also steadily drops.

### Humidity (%) vs. Latitude:

This scatter plot demonstrates how humidity changes as you approach (or depart) the equator (Latitude of 0). The data points are distributed quite equally across this graph, and it does not seem that there is a significant relationship between a city's latitude and humidity. The majority of the cities represented by this plot have relative humidity levels between 60% and 100%. So, regardless of latitude, high humidity is a fact around the globe.

### Cloudiness (%) vs. Latitude:

This one demonstrates how cloudiness alters as you approach (or depart from) the equator (Latitude of 0). On the graph, the data points are distributed rather equally. The majority of cities often have either low or very high levels of cloud cover. Thus, the majority of the data points are close to the extremes. There are other cities, nevertheless, where the level of cloudiness is in the middle. It doesn't seem like there is a direct relationship between a city's latitude and cloudiness because the data points are dispersed.

### Wind Speed (m/s) vs. Latitude:

This scatter plot demonstrates how wind speed changes as you approach (or depart) the equator (Latitude of 0). The data points are grouped around lower values for wind speed. Cities farther from the equator appear to have similar wind speeds as the ones closer. The latitude of a city does not seem to have much of an impact on wind speed.

---

## Linear regression modelling explanation:

### Northern Hemisphere - Temperature (C) vs. Latitude and Southern Hemisphere - Temperature (C) vs. Latitude:

In both the northern and southern hemispheres, the linear regression model is simulating what happens to temperature as latitude increases. Additionally, this implies that as latitude increases in the northern hemisphere, you move farther away from the equator. On the other hand, as we move farther from the equator in the southern hemisphere, latitude gets lower. Latitude and maximum temperature have a strong inverse relationship in the northern hemisphere. The maximum temperature and latitude are positively correlated in the southern hemisphere.

### Northern Hemisphere - Humidity (%) vs. Latitude and Southern Hemisphere - Humidity (%) vs. Latitude:

In both the northern and southern hemispheres, the linear regression is predicting what happens to humidity as latitude rises. We go farther from the equator as latitude grows in the northern hemisphere and closer to the equator as latitude increases in the southern hemisphere. There is no discernible relationship between latitude and humidity.

### Northern Hemisphere - Cloudiness (%) vs. Latitude and Southern Hemisphere - Cloudiness (%) vs. Latitude:

In both the northern and southern hemispheres, the linear regression is predicting what happens to cloudiness as latitude rises. We go farther from the equator as latitude grows in the northern hemisphere and closer to the equator as latitude increases in the southern hemisphere.Although there is a positive correlation it appears that increases in latitude are only slightly correlated to increases in cloudiness for the southern hemisphere. However, in the northern hemisphere, there is no correlation between latitude and cloudiness.

### Northern Hemisphere - Wind Speed (m/s) vs. Latitude and Southern Hemisphere - Wind Speed (m/s) vs. Latitude:

In both the northern and southern hemispheres, the linear regression is predicting what happens to wind speed as latitude rises. We go farther from the equator as latitude grows in the northern hemisphere and closer to the equator as latitude increases in the southern hemisphere. There is no correlation between wind speed and latitude.

---

## Trends description:

1. Both the northern and southern hemispheres are experiencing a rise in temperature in areas near to the equator. This makes sense considering the increasing distance of the north and south from the equator.
2. Humidity is often over 60% in both the northern and southern hemispheres, and it tends in the opposite direction of temperature, which is accurate given that relative humidity rises as temperature falls.
3. Similar to wind speed, cloudiness in both hemispheres varied and showed no latitude-based pattern.