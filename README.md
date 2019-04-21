# Belly Button Biodiversity Analysis


Created interactive dashboard to explore the Belly Button Biodiversity DataSet (http://robdunnlab.com/projects/belly-button-biodiversity/).

## Plotly.js

Used Plotly.js to build interactive charts for your dashboard.

* Created a PIE chart that useed data from your samples route (`/samples/<sample>`) to display the top 10 samples.

  * Used `sample_values` as the values for the PIE chart

  * Used `otu_ids` as the labels for the pie chart

  * Used `otu_labels` as the hovertext for the chart

 * Created a Bubble Chart that used data from  samples route (`/samples/<sample>`) to display each sample.

  * Use `otu_ids` for the x values

  * Use `sample_values` for the y values

  * Use `sample_values` for the marker size

  * Use `otu_ids` for the marker colors

  * Use `otu_labels` for the text values

 * Display the sample metadata from the route `/metadata/<sample>`

  * Display each key/value pair from the metadata JSON object somewhere on the page

* All of the plots will get updated any time that a new sample is selected.


##  Heroku

Deployed your Flask app to Heroku.



## Used Flask API

Use Flask API starter code to serve the data needed for your plots.

* Test your routes by visiting each one in the browser.

