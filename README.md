# Vega-Altair powered web tool to visualize the changes in average land temperatures over the last 250 years
Using Altair, I create a data exploration tool that allows you to view mutliple contries change in measured land temparture over time, both in isolation and in comparison to one or more countries and/or regions. Description of tool and instructions on how to use it below.

### View land temperatures tool [here](https://kyleritland.github.io/kyleritland/vis_earth_temps.html)

The tool allows you to explore the data with 4 seperate but connected charts. The top-left chart has a click-and-drag feature where you can select a specific time range out of the data, and have the other three graphs constrained to show data only from that time span. The left column of charts show average temperatures in absolute terms, while the right column of charts show average temperatures with respect to each countries/regions average over all times in the data set. The top row is in degrees Celcius, while the bottom row is in degrees Fahrenheit. The legend on the far right of the plots is interactive, meaning you can click one or more of the countries/regions and have their data isolated from the full data set and plotted

### To use the chart:
1. On the top-left plot, click and drag your mouse over a time span of interest
2. From the legend on the far right, select the countries and/or regions of interest (you might need to click more than once to get the graphic to register)
3. Rinse and repeat

### Charts shown:
1. Top-left chart: This shows all contries and regions over the full time span of the data, in degrees celcius. Here you can click-and-drag your mouse accross the chart to select a specific time span (i.e. from 1900 to 1950). Selected countries will be shown in prominent colors while unselected countries will be greyed out.
2. Top-right chart: This shows the selected subset of data with respect to each regions average temperature over all time, in degrees celcius. This collection is the set of countries/regions selected from the legend and the time span selected from the top-left chart.
3. Bottom-left chart: This shows the selected subset of data in absolute terms, in degrees fahrenheit. This collection is the set of countries/regions selected from the legend and the time span selected from the top-left chart.
4. Bottom-right chart: This shows the selected subset of data with respect to each regions average temperature over all time, in degrees fahrenheit. This collection is the set of countries/regions selected from the legend and the time span selected from the top-left chart

