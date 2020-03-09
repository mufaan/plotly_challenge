# Plot.ly Homework - Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria_by_filterforgedotcom.jpg)

In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).


## Step 1 - Plotly.js

Use Plotly.js to build interactive charts for your dashboard.

* Create a PIE chart that uses data from your samples route (`/samples/<sample>`) to display the top 10 samples.

  * Use `sample_values` as the values for the PIE chart.

  * Use `otu_ids` as the labels for the pie chart.

  * Use `otu_labels` as the hovertext for the chart.

  ![PIE Chart](Images/pie_chart.png)

* Create a Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.

  * Use `otu_ids` for the x values.

  * Use `sample_values` for the y values.

  * Use `sample_values` for the marker size.

  * Use `sample_values` for the marker colors.

  * Use `otu_labels` for the text values.

  ![Bubble Chart](Images/bubble_chart.png)

* Display the sample metadata from the route `/metadata/<sample>`

  * Display each key/value pair from the metadata JSON object somewhere on the page.

* Update all of the plots any time that a new sample is selected.


## Step 2 - Heroku

Deployed my Flask app to Heroku.

* used the provided sqlite file for the database.

- - -

## Advanced Challenge Assignment

* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the Weekly Washing Frequency obtained from the `/metadata/<sample>`route.

![Weekly Washing Frequency Gauge](Images/gauge.png)

- - -

## Flask API

Used Flask API starter code to serve the data needed for your plots.

* Tested my routes by visiting each one in the browser.

- - -

## Hints

None to state

- - -
