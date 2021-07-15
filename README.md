# D3 Exercise - Getting Comfortable with D3

## Background

In this exercise, I used HTML, Javascript & D3 to leverage a data set from the US Census Bureau (https://data.census.gov/cedsci/), to create an interactive dashboard that displays a scatterplot, where viewers are able to toggle between multiple values for both the X & Y axis. Included in the scatter plot is the ability to hover over each data point for more information, based on what is selected for each axis. 

Below the scatterplot is a brief analysis for each view available in the scatterplot. 


### Core Exercise: D3 Dabbler

Create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3 techniques, create a scatter plot that represents each state with circle elements. You'll code this graphic in the `app.js` file—make sure you pull in the data from `data.csv` by using the `d3.csv` function.

* Include state abbreviations in the circles.
* Create and situate your axes and labels to the left and bottom of the chart.

- - -

### Bonus:

Make an interactive scatterplot with multiple views for the X & Y axis.

#### 1. More Data, More Dynamics

Place additional labels in your scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. Or, for an extreme challenge, create three for each axis.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.

- - -

Zach Liebler, 2021