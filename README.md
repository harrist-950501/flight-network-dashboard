# Global Aviation Network Analysis Dashboard

This project presents an interactive dashboard for exploring the structure of the global aviation network using large-scale flight schedule and airport infrastructure data.  
The analysis focuses on how air traffic is distributed across countries and airports, highlighting patterns of connectivity, hub concentration, and imbalance in global flight activity.

The dashboard combines data processing, statistical summaries, and interactive visualization to examine how a small number of airports and countries dominate the global transportation network.


## Dashboard

The project is implemented in **R** using **Quarto**, with interactive visualizations built using **Ggplot**, **Plotly**, and **DT**.  
The dashboard presents multiple views of the aviation network, including:

- Distribution of total flights by country  
- Concentration of traffic among top airports  
- Comparison between domestic and international connectivity  
- Geographic visualization of airport activity  

The rendered dashboard can be opened directly from the HTML output included in this repository.


## Data Sources

This project draws on two main datasets:

- **Flight schedule data** from  
  https://github.com/MrAirspace/aircraft-flight-schedules  
  Used to analyze traffic volume, route distribution, and global connectivity patterns.

- **Airport metadata** from  
  https://ourairports.com/help/data-dictionary.html  
  Used to identify airport locations, country codes, and geographic structure.

These datasets allow the project to examine how global aviation activity is distributed across airports and countries, and how major hubs shape the overall network.


## Technologies Used

- R  
- Quarto  
- tidyverse  
- plotly  
- arrow  
- DT  


## Note

The dashboard included in this repository was rendered with embedded resources, so it can be viewed without the original flight dataset.

The raw flight schedule data is not included due to its large size.  
To reproduce the project locally, the flight data must be downloaded separately from:

https://github.com/MrAirspace/aircraft-flight-schedules/releases/tag/aircraft_flight_schedules_2025_quarter4

The airport metadata file is included in this repository.
