## Mental Health DALYs Dashboard

This interactive Shiny dashboard visualizes Disability-Adjusted Life Years (DALYs) for mental health disorders across European countries, based on 2021 data.

Key Features
Country-level analysis: Select a country to view a detailed bar chart of DALY rates per 100,000 population by mental health disorder (e.g., depression, anxiety, bipolar disorder).

Each disorder is labeled with its percentage contribution to the country’s total mental health DALYs.

European overview: Explore a color-coded interactive map showing total DALYs by country.

Hover over countries to see their DALY totals and how they compare (as a percentage of the highest-burden country in Europe).

Data Scope
Year: 2021

Population: All ages, Both sexes

Source: https://vizhub.healthdata.org/gbd-results/

To run the app, the following R packages are required:


shiny, 
shinydashboard, 
tidyverse, 
leaflet, 
sf, 
rnaturalearth, 
rnaturalearthdata

##Install any missing packages using install.packages("package_name")


How to Run: Open the app's R script and click “Run App” in RStudio, or use:

shiny::runApp("app_directory_path")

