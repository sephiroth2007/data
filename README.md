# data
Data Covid-19

File project name: VisualizationCovid.zip
- Currently running on pycharm
- Run app.py
- Folder templates has the code in d3.js (home.html)

About the graphs.
- GraphsTentative is the last graph Elliot send like example.  
This is an example static figure that we aim to make it dynamic, The colored lines mark the initiation of the corresponding public health intervention. The solid blue lines represent median, light blue shading represents 50% confidence intervals of the model estimate, and dark blue shading represents 95% confidence intervals of the model estimate. The upper figure in each cluster is the estimated daily reproduction number over time. The dashed horizontal line represents a daily reproduction numberof one. The lower figure in each cluster is the estimated reported cases versus the actual reported cases (black dashed line) by date of onset.
Code abbreviations:
S1: School closing
	S2: Workplace closing
	S3: Cancel public event
	S4: Restrictions on gatherings
	S5: Close public transport
	S6: Stay at home requirements
	S7: Restrictions on internal movement
	S8: International travel controls
	E1: Income support
	E2: Debt/contract relief
	H1: Public information campaigns
	H2: Testing policy
	H3: Contact tracing'
/////////////

Things to do:
Matias
Make corrections Graph 1:
- place a vertical line to the current last day
- adapt to cumulative chart like melbourne
- absolute date on x axis

Akshita
Make corrections Graph 2:
- place a vertical line to the last current day
- adapt graph 2 to area graph.
- place a horizontal line on graph 2 at y = 1
- absolute date on x axis

For area graph I was perhaps thinking of these alternatives:

overlapping areas 
https://bl.ocks.org/interwebjill/8122dd08da9facf8c6ef6676be7da03f

stacked area
https://www.d3-graph-gallery.com/graph/stackedarea_basic.html

If you find any better yet.

I would recommend first:
- Create area chart reading data using R75 and R25.
- Create area chart (R75 and R25) + line chart (R50).

I think the corrections less important are the vertical and horizontal lines. 

Final part (Both):
Joining Graph 1 and 2.

Books:
In the folder books there are books....

I recommend this: D3-Tips-and-Tricks

Data:
covid19_rt_global.csv

Motivation:
https://www.createwithdata.com/d3js-or-chartjs/
https://medium.com/free-code-camp/these-are-the-best-javascript-chart-libraries-for-2019-29782f5e1dc2

Information:

https://www.tutorialspoint.com/d3js/index.htm

https://www.w3schools.com/js/

https://www.tutorialsteacher.com/d3js

http://learnjsdata.com

https://riptutorial.com/d3-js

https://www.dashingd3js.com/table-of-contents

https://www.d3-graph-gallery.com

https://d3js.org

https://bl.ocks.org

https://www.d3indepth.com

https://observablehq.com
https://observablehq.com/@d3/gallery
https://observablehq.com/@d3/learn-d3

https://www.freecodecamp.org/news/learn-d3-js-in-5-minutes-c5ec29fb0725/

https://christopheviau.com/d3list/

https://www.bogotobogo.com/DataVisualization/List_of_D3_Examples.php

Videos
https://www.youtube.com/watch?v=4e3NF8ez95w&list=PL9yYRbwpkykvOXrZumtZWbuaXWHvjD8gi&index=1
https://www.youtube.com/watch?v=_8V5o2UHG0E









