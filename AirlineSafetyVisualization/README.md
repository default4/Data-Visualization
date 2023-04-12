## Overview:

The project aims to visualize airline safety performance using data analysis and visualization techniques. The Python programming language and several popular libraries are employed to preprocess the dataset, perform data analysis, and create interactive visualizations.

## Dependencies:

* Python 3.7+
* Pandas
* Numpy
* Requests
* Plotly

To install the required libraries, run the following command:

```
pip install pandas numpy requests plotly
```

## Dataset:

The dataset used in this project is the Airline Safety dataset, which contains information about airline incidents and accidents from 1985 to 2014. The dataset can be downloaded directly using the provided URL:

* Airline Safety Dataset: https://raw.githubusercontent.com/fivethirtyeight/data/master/airline-safety/airline-safety.csv

In the scatter plot, each point represents an airline. The x-axis shows the number of incidents from 1985 to 1999, and the y-axis shows the number of incidents from 2000 to 2014. The size of each point is determined by the number of fatal accidents that occurred between 2000 and 2014. The color of each point represents the number of fatalities between 2000 and 2014, with a color scale that ranges from light to dark colors, indicating an increase in the number of fatalities.

When hovering over a point on the plot, the airline's name will be displayed, along with the respective values for incidents, fatal accidents, and fatalities for the corresponding time periods.

Furthermore, a trendline is added to the plot using Ordinary Least Squares (OLS) regression. This trendline helps identify any relationship or pattern between the number of incidents in the two time periods (1985-1999 and 2000-2014).

Overall, this plot provides a visual representation of airline safety performance, enabling users to analyze and compare different airlines based on their safety records over time.
