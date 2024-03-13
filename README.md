# SpaceX Launch Records Dashboard

This interactive web dashboard is built with [Dash](https://plotly.com/dash/) and [Plotly Express](https://plotly.com/python/plotly-express/), designed to visualize the SpaceX Falcon 9 launch records. Users can filter launch sites, visualize launch success rates, and explore the correlation between payload mass and launch outcomes.

## Key Libraries

- **pandas**: For data manipulation and analysis.
- **dash**: A Python framework for building reactive web apps.
- **html & dcc** from dash: To create HTML components and interactive Graphs for the dashboard.
- **plotly.express**: For creating interactive plots.

## Key Features

- **Launch Site Selection**: A dropdown allows users to filter records by launch sites, including an "All sites" option.
- **Success Rate Visualization**: A pie chart displays the total successful launches count for the selected site or all sites.
- **Payload Range Selector**: A range slider lets users select the payload mass range to filter the launch records.
- **Success-Payload Correlation**: A scatter plot visualizes the relationship between payload mass and launch success.

## Processes Involved

1. Data loading and preprocessing with pandas.
2. Layout setup using Dash html and dcc components.
3. Interactive filtering with callback functions responding to user input.
4. Dynamic chart updates to reflect filtered data, utilizing plotly.express.

---

To get started, clone this repository and run the provided Python script to launch the dashboard on your local server, where you can interact with the SpaceX Falcon 9 launch data.
