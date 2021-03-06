# Belly Button Biodiversity

## Overview:

In this assignment, the microbial diversity that inhabit belly buttons was analyzed. An interactive dashboard was created to visualize belly button biodiversity using JavaScript, D3 and Plotly.


## Datasets:

The dataset was obtained from a study that catalogs the microbes that colonize human navels. The study characterizes the microbial species (also called operational taxonomic units, or OTUs) that were present in more than 70% of people. Each bacterial culture is classified by an OTU ID. OTU, or operational taxonomic units, are used to identify groups of bacteria with similar genetic sequences. The dataset contains the OTU ID, each individual's ID, and metadata displaying each individual's demographic information.


## Workflow:

In the app.js file, JavaScript was used to read the json file and determine the OTU ID and amount found in each individual's navel. D3 was used for animations, click events, and to create a table that displays demographic information for each individual. CSS was used for styling and Plotly was used to visualize the results in two graphs. The individual ID can be selected to display that individuals information in the table and graphs.


## Graphs:

For each test subject, the top 10 bacterial cultures found in their navel are displayed in the bar graph. 

<img src="images/chartPlotly.png" width="600">

The bubble graph displays the top 10 bacterial cultures, but the marker size is determined by the amount of that bacterial culture compared to the other bacterial cultures found in that individual's navel.

<img src="images/BubblegraphPlotly.png" width="600">
