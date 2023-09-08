# earthquake_visualize_r

## Visualization project

### Overview of visualization
The global earthquake data visualization project provides a user-friendly overview of earthquake patterns and trends, offering insights not easily gleaned from text or numbers alone. Earthquakes are natural disasters with far-reaching impacts, and this visualization aids in decision-making related to land use, construction, and infrastructure development. By using the versatile R platform, interactive dashboards enhance users' understanding of earthquake data. The project's key objectives are to identify high-risk areas, improve disaster preparedness by analyzing earthquake frequency and distribution over time, and gain insights into tectonic processes by examining relationships between earthquake magnitude, depth, and location.

### Dataset
The dataset used in this project is the "Significant Earthquakes, 1965-2016" dataset from Kaggle, comprising 23,413 observations and 21 columns. The key variables of interest are: Date, Time, Latitude, Longitude, Type, Depth, Magnitude, and Magnitude Type. These variables provide information about the date, time, location, type, depth, and magnitude of significant earthquakes, making it a valuable resource for studying earthquake patterns and their impacts.

### Limitation of dataset
• The dataset only covers the period from 1965 to 2016, and more recent earthquake events are not included.
• The dataset primarily focuses on significant earthquakes, which may exclude smaller earthquakes that still have notable impacts on local communities.
• Some variables within the dataset have missing or incomplete data, which may affect the accuracy of the analysis.

### Visualization design process
In this visualization project, five interactive visuals were created using R. These visuals were designed to be interactive, dynamic, and informative, employing various R packages. The primary goal was to enhance data comprehension and enable more effective data-driven decision-making.

#### 1 Interactive map of the world
The interactive world map is a user-friendly tool that visualizes the geographical distribution of earthquakes. It allows users to explore and analyze patterns by zooming and clicking on specific regions. Earthquake events are represented by markers, with a popup appearing when clicked, showing information such as magnitude, depth, and date. The markers are color-coded using green for areas with lower earthquake density and red for those with higher density. This approach enables users to quickly identify patterns and seismic activity levels across the globe, making the map an effective visualization tool. It helps users focus on areas of interest and identify high-risk locations and trends in seismic activity.
<img width="639" alt="image" src="https://github.com/jiraratset/earthquake_visualize_r/assets/123735686/1f54c7b8-7c82-4cfc-89b8-f350cbb4674a">

#### 2 Interactive line chart
The visualization uses a line graph and two bar charts to display different aspects of earthquake events. The line chart shows the yearly count of earthquakes from 1965 to 2016, while the bar charts present the average number of monthly earthquakes and earthquakes per day of a month. These visualizations help identify patterns and when earthquakes occur more frequently. The charts use blue color for accessibility and have a clean background for easy readability.
<img width="434" alt="image" src="https://github.com/jiraratset/earthquake_visualize_r/assets/123735686/b567c0fe-a2c8-40d7-81ac-a44175db8f8f">

#### 3 Interactive data table
The interactive data table is designed to display large amounts of earthquake data in a tabular format. It includes information about the country, year, magnitude, and depth of each earthquake. Users can interact with the table to sort, filter, and search through the data, allowing for in-depth exploration and analysis. This tool enables users to quickly find specific information and identify patterns and trends in the data.
<img width="644" alt="image" src="https://github.com/jiraratset/earthquake_visualize_r/assets/123735686/6b16c409-729f-4943-99e4-1a93059f0189">

### Full dashboard
<img width="1077" alt="image" src="https://github.com/jiraratset/earthquake_visualize_r/assets/123735686/00ea7175-302f-4738-ba1b-792b5a5d5653">


