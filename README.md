# Belly Button Biodiversity (Dashboard w/ Plotly)
## Overview of Project
> Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

1. ***Deliverable 1***: Create a Horizontal Bar Chart
2. ***Deliverable 2***: Create a Bubble Chart
3. ***Deliverable 3***: Create a Gauge Chart
4. ***Deliverable 4***: Customize the Dashboard
5. ***Deliverable 5***: A written report on the Belly Button Biodiversity Dashboard analysis [`README.md`](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity). 

# Deliverable 1:  
## Create a Horizontal Bar Chart
### Deliverable Requirements:
Using your knowledge of JavaScript, Plotly, and D3.js, create a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart will display the `sample_values` as the values, the `otu_ids` as the labels, and the `otu_labels` as the hover text for the bars on the chart.

Your bar chart should look like the following image:

![name-of-you-image](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity/blob/main/Resources/Images/bar_chart.PNG)


1. Code is written to create the arrays when a sample is selected from the dropdown menu.
2. Code is written to create the trace object in the `buildCharts()` function, and it contains the following:
    - The y values are the `otu_ids` in descending order.
    - The x values are the `sample_values` in descending order
    - The hover text is the `otu_labels` in descending order.
3. Code is written to create the layout array in the `buildCharts()` function that creates a title for the chart.
4. When the dashboard is first opened in a browser, **ID 940**’s data should be displayed in the dashboard, and the bar chart has the following:
    - The top 10 `sample_values` are sorted in descending order
    - The top 10 `sample_values` as values
    - The `otu_ids` as the labels

# Deliverable 2:  
## Create a Bubble Chart
### Deliverable Requirements:
Using your knowledge of JavaScript, Plotly, and D3.js, create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:

- The `otu_ids` as the x-axis values.
- The `sample_values` as the y-axis values.
- The `sample_values` as the marker size.
- The `otu_ids` as the marker colors.
- The `otu_labels` as the hover-text values.

Your bubble chart should look like the following image:

![name-of-you-image](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity/blob/main/Resources/Images/bubble_chart.PNG)

1. The code for the trace object in the `buildCharts()`; function does the following:
    - Sets the `otu_ids` as the x-axis values
    - Sets the `sample_values` as the y-axis values
    - Sets the `otu_labels` as the hover-text values
    - Sets the `sample_values` as the marker size
    - Sets the `otu_ids` as the marker colors
2. The code for the layout in the `buildCharts()`; function does the following:
    - Creates a title
    - Creates a label for the x-axis
    - The text for a bubble is shown when hovered over
3. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu

# Deliverable 3:  
## Create a Gauge Chart
### Deliverable Requirements:
Using your knowledge of JavaScript, Plotly, and D3.js, create a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

Your gauge chart should look similar to the following image:

![name-of-you-image](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity/blob/main/Resources/Images/gauge_chart.PNG)

1. The code to build the gauge chart does the following:
    - Creates a title for the chart.
    - Creates the ranges for the gauge in increments of two, with a different color for each increment.
    - Adds the washing frequency value on the gauge chart.
    - The indicator shows the level for the washing frequency on the gauge.
    - The gauge is added to the dashboard.
    - The gauge fits in the margin of the `<div>` element.
2. When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable

# Deliverable 4:  
## Customize the Dashboard
### Deliverable Requirements:
Use your knowledge of HTML and Bootstrap to customize the webpage for your dashboard.

1. Customize your dashboard with three of the following:
    - Add an image to the jumbotron.
    - Add background color or a variety of compatible colors to the webpage.
    - Use a custom font with contrast for the colors.
    - Add more information about the project as a paragraph on the page.
    - Add information about what each graph visualizes, either under or next to each graph.
    - Make the webpage mobile-responsive.
    - Change the layout of the page.
    - Add a navigation bar that allows you to select the bar or bubble chart on the page.
2. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the three charts should be working according to their requirements.
3. When a sample is selected, the dashboard should display the data in the panel and all three charts according to their requirements.

 
### Results with detail analysis:

1. **Customize your dashboard with three of the following:**
    - Add an image to the jumbotron.
    - Add background color or a variety of compatible colors to the webpage.
    - Use a custom font with contrast for the colors.
    - Add more information about the project as a paragraph on the page.
    - Add information about what each graph visualizes, either under or next to each graph.
    - Make the webpage mobile-responsive.
    - Change the layout of the page.
    - Add a navigation bar that allows you to select the bar or bubble chart on the page.

> Plots downloaded as `.png`

![name-of-you-image](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity/blob/main/Resources/Images/newplot%20(1).png)

![name-of-you-image](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity/blob/main/Resources/Images/newplot%20(2).png)

![name-of-you-image](https://github.com/DataJew/Plotly-Belly-Button-Biodiversity/blob/main/Resources/Images/newplot%20(3).png)

> Visit the dasboard produced with Plotly below!

[`Belly Button Biodiversity Dashboard`](https://datajew.github.io/Plotly-Belly-Button-Biodiversity/)
