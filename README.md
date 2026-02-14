## Manchester Energy Efficiency Insights Dashboard ##

## Project Overview ##

This project presents an interactive Energy Performance Certificate (EPC) Analytics Dashboard focused on Manchester (2014–2024).

Using SQL Server, Power BI, and Advanced DAX, the dashboard analyzes building energy performance, CO₂ emissions, energy consumption, cost distribution, and efficiency improvement potential.

The goal of this project is to transform complex EPC data into clear, actionable insights that support sustainability planning, carbon reduction strategies, and data-driven decision-making.


## Data Source ##

- UK Domestic EPC Dataset

- Source: https://epc.opendatacommunities.org

- Local Authority: Manchester

- Period: 2014–2024


## Tools & Technologies ##

- Microsoft SQL Server – Data import, cleaning, transformation

- T-SQL – Handling null values, removing “NO DATA”, filtering columns

- Microsoft Power BI – Data modeling and dashboard creation

- DAX (Data Analysis Expressions) – Efficiency gain, cost calculations, CO₂ reduction measures

## Methodology ##

## Data Preparation (SQL Server) ##

- Imported raw EPC dataset

- Removed unnecessary columns

- Converted “NO DATA” values to NULL

- Deleted incomplete records

- Cleaned and structured final dataset

## Data Modeling (Power BI) ##

- Built calculated measures using DAX

- Created efficiency gain percentage

- Calculated CO₂ reduction potential

- Computed average energy cost savings



## Dashboard Features ##
CO₂ vs Efficiency Density View

- Shows inverse relationship between energy efficiency and CO₂ emissions

- Higher EPC ratings = Lower emissions

Cost Distribution

- Heating identified as the largest energy cost driver

- Houses show the highest total energy costs

Efficiency Improvement Potential

- Houses show the highest improvement potential (~29%)

- Flats show lower improvement need (~10–13%)

Energy Flow Overview (Sankey Chart)

Visualizes energy movement across property types

- Larger properties show higher energy flow

Current vs Potential Comparison

- All property types show improved efficiency and reduced emissions at potential levels

Efficiency Target Tracking

- Tracks progress toward a 20% efficiency improvement goal

Card Visualizations

- Average Energy Cost Saving

- CO₂ Reduction Potential

Interactive Slicers

- Property Type

- Building Form

- Transaction Type


## Key Insights ##

- Higher energy efficiency directly reduces CO₂ emissions.

- Heating is the primary contributor to energy costs.

- Houses and larger dwellings have the greatest improvement potential.

- All property types show measurable carbon reduction opportunities.

- Targeted upgrades can significantly reduce environmental and financial costs.


## Conclusion ##

This dashboard demonstrates how data analytics can support climate action and sustainable urban development.

By integrating SQL data cleaning, advanced DAX modeling, and interactive Power BI visualization, the project highlights how building-level EPC data can guide energy renovation strategies and carbon reduction planning in Manchester
