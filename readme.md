# Global warming: Contributions to the change in global mean surface temperature - Data package

This data package contains the data that powers the chart ["Global warming: Contributions to the change in global mean surface temperature"](https://ourworldindata.org/grapher/contributions-global-temp-change?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website. It was downloaded on December 01, 2024.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The final column is the data column, which is the time series that powers the chart. If the CSV data is downloaded using the "full data" option, then the column corresponds to the time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data column is transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

## Detailed information about the data


## Share of contribution to global warming
Measured as a percentage of the world's temperature change.
Last updated: November 21, 2024  
Next update: November 2025  
Date range: 1851–2023  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Jones et al. (2024) – with major processing by Our World in Data

#### Full citation
Jones et al. (2024) – with major processing by Our World in Data. “Share of contribution to global warming” [dataset]. Jones et al., “National contributions to climate change 2024.2” [original data].
Source: Jones et al. (2024) – with major processing by Our World In Data

### What you should know about this data
* This temperature change measures each country's contribution to global mean surface temperature (GMST) rise from its cumulative emissions of carbon dioxide, methane and nitrous oxide.
* The warming effects of each gas are calculated based on cumulative CO₂-equivalent emissions using the Global Warming Potential (GWP*) approach.

### Source

#### Jones et al. – National contributions to climate change
Retrieved on: 2024-11-21  
Retrieved from: https://zenodo.org/records/7636699/latest  


    