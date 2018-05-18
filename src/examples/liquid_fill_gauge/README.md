#  Liquid Fill Gauge

![](/Users/4mile/Documents/github/custom_visualizations_v2/src/examples/liquid_fill_gauge/liquid_fill_gauge.png)
 
This diagram displays a liquid fill gauge (LFG), showing either the value or percentage of one measure compared to either another value or 100%, respectively.



****
add .mov file once we have the lfg working on the looker hosted instance
****

**How it Works**

Create an explore with one or more measures, and no dimensions. 

**More Info**

The liquid fill gauge visualization is used to display one measure, either in relation to another larger measure, or as a percent of 100. If relating to another measure, the first measure can be displayed as either a percent of the larger measure or the value itself. The visualization represents a thermometer, filling up as the measure gets closer to equivalence with the larger measure (or 100).

Including any dimensions in the query will either have no effect or will cause the measure to aggregate at a more granular level, in which case the visualization will display the top (in result grid) value of the first measure, compared to the top value of the second measure. 



[![](sankey/sankey.png)](/sankey/sankey.js)
