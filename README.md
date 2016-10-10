# CS5331-Visualization-Project1
## Visualizing Time Series Data
Visualizing time series data, the unemployment rate of all the states of the US is represented in various ways as per the provided instructions. This project provides the analysis of the discrepancies between the unemployment rates in various states of the USA in the time scale of 1980-2016.The principle source of the data used in this project is http://www.bls.gov/data. The major applications used are JavaScript and d3.
### DESIGN AND PROCEDURE FOR PROJECT
** STEP1: **	
Here, we worked on the unemployment data for all the states in the US which is available on Bureau of Labor and statistics.
Firstly, we need to set up an account in GITHUB.
From d3js.org I have selected a US political map. Then from the multiple series line chart, extracted the code for multiple state graph.	Later I have integrated the graph and the map to be interactive.
[![ScreenShot](https://github.com/aktummal/CS5331-Visualization-Project1/blob/master/1.PNG)]
** STEP2: **
The project is interactive now, when you click on the state in the map we get the respective unemployment rate graph.
[![ScreenShot](https://github.com/aktummal/CS5331-Visualization-Project1/blob/master/2.PNG)]
** STEP3: **
We can also select multiple states at the same time. I also have added a tooltip, which shows the name of the state and the respective date on pointing over the graph and added the feature to deselect the state for the respective graph to disappear.
I used a slider to zoom the graph
[![ScreenShot](https://github.com/aktummal/CS5331-Visualization-Project1/blob/master/3.PNG)]
** STEP4: **
[![ScreenShot](https://github.com/aktummal/CS5331-Visualization-Project1/blob/master/4.PNG)]
I have added two checkboxes 
1}select all
2)national unemployment rate
*Select all* check box is to show the US states unemployment rate graph all together in multiple line graph.
*national unemployment rate* shows the average of all the US states unemployment rate.
[![ScreenShot](https://github.com/aktummal/CS5331-Visualization-Project1/blob/master/5.PNG)]
### SOURCES AND REFERENCES
http://www.bls.gov/data - main source of project.
https://bl.ocks.org/wrobstory/7612013 -zooming and slider
http://www.d3noob.org/2012/12/adding-axis-labels-to-d3js-graph.html -adding axis labels
https://vida.io/gists/FLFFovRPbu2t5QwQC - US state map
http://bl.ocks.org/mbostock/3883245 - single line graph
http://bl.ocks.org/mbostock/3884955 -multiple time series
