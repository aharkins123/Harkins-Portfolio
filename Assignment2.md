# Assignment 2

### Part One

<iframe src="https://data.oecd.org/chart/6vsN" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</iframe>

### Part Two - Grid of Line Charts

Displayed here is a grid of line charts for the debt-to-GDP ratio for 47 countries. The y-axis details the debt-to-GDP ratio (as a percent) and the x-axis depicts the year, ranging from 1995 to 2020. Viewers might take note of the rapidly increasing ratios for countries such as Japan and Greece. 
<div class="flourish-embed flourish-chart" data-src="visualisation/7690930"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Part Two - Own Visualization

Displayed below is a scatterplot of each country's debt-to-GDP ratio from 1995 to 2020. 

<div class="flourish-embed flourish-scatter" data-src="visualisation/7691304"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This method of visualization, compared to the first grid of line charts, gives a better sense of the overall movement in debt-to-gdp ratio over time. While the first visualization provided users the ability to instantly spot a country and see its individual debt-to-GDP ratio over time, the big picture was lost with the separate grid of 47 line charts. For this reason, I created a scatterplot that does not color the points by country, but does quickly give viewers an idea of the spread of debt-to-gdp ratios over time. Moreso than the first visualization, this allows the viewer to quickly recognize that the overall spread of debt-to-gdp ratios has increased over time, starting at a minimum of around 10% and a maximum of 140%, and moving to a minimum of around 25% and a maximum of around 250%. To reinforce this understanding of overall movement in debt-to-gdp ratios, I included a trend line that shows the slight increase in overall debt-to-gdp ratios over time. 

While this scatter plot visualization loses some of the specificity provided by the first visualization, I included an interactive filter that allows users to select a specific country to display. This way, viewers who are still interested in finding details about a specific country's debt-to-ratio can do so. While Flourish automatically adjusts axes for these filtered scatterplots, I opted to not allow the y-axis to shift depending on the country being viewed. This allows the viewer to filter by country but still have a solid understanding of where that country's debt-to-gdp ratio falls relative to all other countries in the dataset.
