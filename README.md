# Plotly
Create an interactive data visualization for the web using `HTML` and basic `JavaScript`

## Overview
Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

## Deliverable 1

**Directions:**

1. Create a variable that has the array for all the samples.
2. Create a variable that will hold an array that contains all the data from the new sample that is chosen from the dropdown menu. To retrieve the data from the new sample, filter the variable created in Step 2 for the sample `id` that matches the new sample `id` chosen from the dropdown menu and passed into the `buildCharts()` function as the argument.
3. Create a variable that holds the first sample in the array.
4. Create variables that have arrays for `otu_ids`, `otu_labels`, and `sample_values`.
5. Create the yticks for the bar chart.
6. Create the trace object for the bar chart, where the x values are the sample_values and the hover text for the bars are the `otu_labels` in descending order.
7. Create the layout for the bar chart that includes a title.
8. Use the `Plotly.newPlot()` function to plot the trace object with the layout.

**Results:**

<img width="761" alt="D1-1" src="https://user-images.githubusercontent.com/95068439/166170550-b92b51d4-0a44-4328-9ead-c7a65df169f8.png">

<img width="444" alt="D1-2" src="https://user-images.githubusercontent.com/95068439/166170554-56810bfe-fce5-45ae-8a23-ff55bba4834a.png">

<img width="800" alt="D1-3" src="https://user-images.githubusercontent.com/95068439/166170606-28cd52a1-e812-46b3-8713-4abe11a07986.png">

## Deliverable 2

**Directions**
Using your knowledge of JavaScript, Plotly, and D3.js, create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:

* The otu_ids as the x-axis values.
* The sample_values as the y-axis values.
* The sample_values as the marker size.
* The otu_ids as the marker colors.
* The otu_labels as the hover-text values.

**Results:**

<img width="566" alt="D2-1" src="https://user-images.githubusercontent.com/95068439/166170848-5bd8b21b-a9f2-4eeb-90a9-166674f889ee.png">

<img width="618" alt="D2-2" src="https://user-images.githubusercontent.com/95068439/166170850-bfe64dad-6e89-47a5-aaea-1d933e46b333.png">

## Deliverable 3

**Directions:**
1. Create a variable that filters the metadata array for an object in the array whose id property matches the ID number passed into `buildCharts()` function as the argument.
2. Create a variable that holds the first sample in the array created in Step 1.
3. Create a variable that converts the washing frequency to a floating point number.
4. Create the trace object for the gauge chart.
5. Create the layout for the gauge chart making sure that it fits in the `<div></div>` tag for the gauge id.
6. Use the `Plotly.newPlot()` function to plot the trace object and the layout.

**Results:**

<img width="842" alt="D3-1" src="https://user-images.githubusercontent.com/95068439/166171416-941fde56-5cf3-4e3e-bab6-0ceb5d55ddb6.png">

<img width="472" alt="D3-2" src="https://user-images.githubusercontent.com/95068439/166171419-0caa90e7-263d-4571-961c-36f2d18f98af.png">

<img width="733" alt="D3-3" src="https://user-images.githubusercontent.com/95068439/166171484-a6a5c1e6-0ac4-463e-b0c5-13d2b1bc7a6b.png">

## Deliverable 4

**Directions:**
Use your knowledge of HTML and Bootstrap to customize the webpage for your dashboard.

1. Customize your dashboard with three of the following:
* Add an image to the jumbotron.
* Add background color or a variety of compatible colors to the webpage.
* Use a custom font with contrast for the colors.
* Add more information about the project as a paragraph on the page.
* Add information about what each graph visualizes, either under or next to each graph.
* Make the webpage mobile-responsive.
* Change the layout of the page.
* Add a navigation bar that allows you to select the bar or bubble chart on the page.
2. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the three charts should be working according to their requirements.
3. When a sample is selected, the dashboard should display the data in the panel and all three charts according to their requirements.

**Results:**

<img width="456" alt="D4-1" src="https://user-images.githubusercontent.com/95068439/166171673-78fd4ebc-61df-4692-bb7f-af33dfb50319.png">

<img width="817" alt="D4-2" src="https://user-images.githubusercontent.com/95068439/166171679-7abb0c51-a12c-48a9-bb17-0828948ab9bb.png">


> LinkedIn: https://www.linkedin.com/in/wilson-alexei/

> Email: wils.alexei@gmail.com


