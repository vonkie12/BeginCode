# Levelized cost of energy for renewables by country - Data package

This data package contains the data that powers the chart ["Levelized cost of energy for renewables by country"](https://ourworldindata.org/grapher/levelized-cost-of-energy?v=1&csvType=full&useColumnShortNames=false&utm_source=chatgpt.com) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For normal countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.

## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Bioenergy levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 2010–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Bioenergy levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


## Geothermal levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 2007–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Geothermal levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


## Offshore wind levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 2000–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Offshore wind levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


## Solar photovoltaic levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 2010–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Solar photovoltaic levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


## Concentrated solar power levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 2010–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Concentrated solar power levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


## Hydropower levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 2010–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Hydropower levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


## Onshore wind levelized cost of energy
This data is expressed in US dollars per kilowatt-hour. It is adjusted for inflation but does not account for differences in living costs between countries.
Last updated: November 15, 2024  
Next update: November 2025  
Date range: 1984–2023  
Unit: constant 2023 US$ per kilowatt-hour  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
IRENA (2024) – with minor processing by Our World in Data

#### Full citation
IRENA (2024) – with minor processing by Our World in Data. “Onshore wind levelized cost of energy” [dataset]. IRENA, “Renewable Power Generation Costs” [original data].
Source: IRENA (2024) – with minor processing by Our World In Data

### What you should know about this data
* Levelized cost of energy (LCOE) estimates the average cost per unit of energy generated across the lifetime of a new power plant. It is measured in US$ per kilowatt-hour.

### Source

#### IRENA – Renewable Power Generation Costs
Retrieved on: 2024-11-15  
Retrieved from: https://www.irena.org/Publications/2024/Sep/Renewable-Power-Generation-Costs-in-2023  


    