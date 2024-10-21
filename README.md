# MedDev
Title of Final Project: MedDev
Group Number: 13
Student Name: Sam Goldberg
Student Name: Siem Yonas
Date: 10/8/2024

Thesis
For this project, we wanted to explore the medical equipment sector and the development of this industry across the globe. In particular, we wanted to explore how the industry has grown over time and the distribution of medical devices across different countries based on where manufacturers were located and where imports and exports were coming from and going to. The ultimate goal of this project is to allow us to view the trajectory of the field and to predict how the industry will shift in the coming years.

Visualization Tools
List the tools
Reasons for using those tools
For our project, we decided to use Plotly and house our visualizations in a Dash app. With its integration of Plotly, React, and Flask along with its modern UI elements, Dash is a quick and dependable way to create these dashboards, especially in the ML and data science space.
Plotly allows us to make line charts, bar charts, and geographic visualizations with robust interactivity with ease, all in Python. Dash and Plotly also have great integration, making this a prime choice for our project.

Argument Layout
Present in a bulleted form your argument 
The medical device industry is still viable for a career, as it is still rapidly growing.
Throughout the years, devices for Surgery have been dominating the industry.
The manufacturing of medical devices abroad has increased dramatically over recent years.
Novel medical devices have trended towards higher device classes over the years.
The geographical distribution of medical device importers reveals a shift towards emerging markets.

Visual Layout
Describe the visual(s) that go with each argument
Describe the interactivity
Describe the layout, choice of colors, annotations (if any), and legends (if any).
- For argument 1, we will have a stacked area chart of Year vs Count of Devices. There will be a slider that restricts the time domain. There will also be an option to set the scale of the plot between linear and semilogy. The plot will also adapt to the geoscope selected. The graph will be colored according to the top 5 device types. The legend will indicate what device type represents each bar when a particular device type is selected. Tooltips/annotations will provide information on the specific device count for a particular year for that particular device type upon hovering over a particular point. The chart will maintain consistency with the Plotly Plasma color scheme used throughout the dashboard.
- For argument 2, there will be a bar chart of the top 5 medical specializations in terms of their device count. The plot will react to the year slider and geoscope selected. The color of each bar will encode the number of unique device types the specialization is associated with. The legend will show the color scale for the number of unique device types. The tooltip will provide information on the number of devices in total and the number of unique device types for a particular medical specialization upon hovering over a particular bar. The chart will maintain consistency with the Plotly Plasma color scheme used throughout the dashboard.
- For argument 3, there will be a global choropleth. The color of each country will indicate the number of manufacturers present. There will be a filter to allow the user to choose a geoscope, which will also update all the other visualizations respectively. The map will react to the year slider as well. The legend will show the color scale for the choropleth (number of manufacturers). Upon hovering over a country, a tooltip will detail the number of manufacturers and the number of devices corresponding to the country. The chart will maintain consistency with the Plotly Plasma color scheme used throughout the dashboard.
- For argument 4, there will be a bar chart of the corresponding medical device classes in terms of their device count. The plot will react to the year slider and geoscope selected. The bar will have stacked coloring based on the top five device types. The legend will indicate the colors each device type corresponds to. The tooltip will detail the number of devices for the corresponding medical device class upon hovering over a particular bar. The chart will maintain consistency with the Plotly Plasma color scheme used throughout the dashboard.
- For argument 5, there will be a choropleth map displaying the number of medical device importers per country. The color intensity of each country will represent the number of importers registered in that region, based on data from different years. The map will react to the year slider and geoscope selections, allowing users to explore how the distribution of importers changes over time. A legend will show the color scale indicating the number of importers. Hovering over a country will reveal a tooltip with detailed information on the number of importers, major cities involved, and any significant changes from previous years. The map will maintain consistency with the Plotly Plasma color scheme used throughout the dashboard.
