# ESG and financial data in Python
## Aims
- The aim of this project is to clean, analyse and generate visualisations in Python with a ESG and financial dataset found on Kaggle: https://www.kaggle.com/datasets/shriyashjagtap/esg-and-financial-performance-dataset
- To be able to understand how sustainability score impacts revenue generated
- Model how changes would impact future revenue

## Methods
###Use Pandas to import and clean data
- The file was imported as a CSV into Jupyter notebook
- To clean the data, the "MarketCap" and "CompanyName" columns were removed as they were not relevant for the task

###Analysis using Pandas
- The groupby and aggregation functions were used to manipulate the data such as to show distribution of companies across industries and regions
- Same functions were used to find out total water usage, carbon emissions and energy consumption over time as well as distribution per industry
- Same functions to show how ESG scores individually and overall have change over time and how they vary per industry

###Generating visualisations using Pandas
- Line graphs were generated using the .plot() function to show variation over time
- Bar charts were used to show variation per industry using the kind = bar with plot()
- Pie charts were made to show company distribution over region and industry

## Outcomes


## Future Steps
