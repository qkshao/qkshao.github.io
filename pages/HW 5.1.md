---
layout: page
title: HW 5.1
permalink: /hw5/
---
<script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>
# Homework 5.1
## Visualization 1
<div id="vis1"></div>
<script type="text/javascript">
var spec1 = "https://qkshao.github.io/assets/js/chart1.json";
vegaEmbed('#vis1', spec1);
</script>
For my first visualization it shows the number of licenses for each license type in the dataset. I used a bar chart where 
the x-axis represents the count of licenses and the y-axis represents the license type. I also used color to differentiate 
between the different license types, which makes the chart easier to read. I chose this design because bar charts are effective 
for comparing counts across categories. No major data transformations were needed for this plot since the counts were calculated 
directly within the visualization.

## Visualization 2
<div id="vis2"></div>
<script type="text/javascript">
var spec2 = "https://qkshao.github.io/assets/js/chart2.json";
vegaEmbed('#vis2', spec2);
</script>
The second visualization I created shows the distribution of license statuses, such as active or not renewed, for different license 
types. The x-axis represents the license status and the y-axis represents the count of licenses. I used color to show the differences
between different license statuses. I chose this design because it allows for easy comparison of how license statuses vary across 
different categories.

## Interactivity
This visualization includes an interactive dropdown menu that allows the user to select a specific license type. When a type is selected, 
the chart updates to show only the data for that category. This makes the visualization more clear and focused, since users can explore 
specific subsets of the data instead of viewing everything at once. This type of interactivity helps improve understanding by allowing users 
to control what they want to see.

## Links
- Data: https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv
- Notebook: https://github.com/qkshao/qkshao.github.io/blob/main/python_notebooks/licenses_analysis.ipynb
