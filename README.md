# Australian-Wildfire-Dashboard

This project is an interactive Dash dashboard that visualizes historical wildfire data in Australia. Users can explore wildfires by region and year, and view key statistics such as the average fire area and the count of pixels for presumed vegetation fires.

📊 Features

Interactive region selection (New South Wales, Northern Territory, Queensland, South Australia, Tasmania, Victoria, Western Australia).

Year selection dropdown to filter data.

Pie chart showing monthly average estimated fire area.

Bar chart showing monthly average count of pixels for presumed vegetation fires.

Built using Dash, Plotly, and Pandas for interactive visualizations.

## How to Run

Open the project folder in your Python environment.

Run the app.py (or the filename of your dashboard script):

python app.py


Open your browser and go to:

http://127.0.0.1:8050/

## Dataset

The dashboard uses historical wildfire data from IBM Developer Skills Network:

CSV file URL: Historical_Wildfires.csv

The dataset includes columns like:

Date – Date of the wildfire

Region – Australian region

Estimated_fire_area – Fire area in hectares

Count – Number of pixels for presumed vegetation fires

Note: The dataset is loaded directly from the URL in this project. You can also download it locally for offline use.

## Code Structure

app.py – Main Dash application file

Libraries used:

pandas for data handling

dash and dash.dependencies for building the interactive dashboard

plotly.express and plotly.graph_objects for visualization

Key components:

Radio buttons for region selection

Dropdown for year selection

Callback function updates two graphs based on user input

## Observations

Certain regions and months show higher fire activity.

Visualization helps identify peak wildfire months and region-wise trends.

Dashboard can be extended for real-time wildfire data or additional metrics.

## References

[Dash Documentation

Plotly Express Documentation 

IBM Skills Network Wildfire Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Historical_Wildfires.csv)
