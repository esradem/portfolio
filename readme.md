# Esra's Portfolio Project

# Introduction
## Aim:
To assess the evolution and impact of renewable energy sources on the total primary energy supply from 1960 to 2015.

## Scope:
- Renewable energy sources including hydro (excluding pumped storage), geothermal, solar, wind, tide, and wave.
+ Bioenergy sources such as solid biofuels, biogasoline, biodiesels, other liquid biofuels, biogases, and the renewable fraction of municipal waste.
* Definition and inclusion criteria for biofuels and municipal waste in the context of renewable energy.

## Data Collection
### Sources:
This dataset is collected from Kaggle.
Historical energy statistics from international energy agencies, national governments, and research institutions.
Data on renewable energy production and consumption, categorized by source (hydro, wind, solar, etc.).
Information on the primary energy equivalent conversion for various renewable sources. " Energy derived from solid biofuels, biogasoline, biodiesels, other liquid biofuels, biogases and the renewable fraction of municipal waste are also included. Biofuels are defined as fuels derived directly or indirectly from biomass (material obtained from living or recently living organisms). This includes wood, vegetal waste (including wood waste and crops used for energy production), ethanol, animal materials/wastes and sulphite lyes. Municipal waste comprises wastes produced by the residential, commercial and public service sectors that are collected by local authorities for disposal in a central location for the production of heat and/or power. This indicator is measured in thousand toe (tonne of oil equivalent) as well as in percentage of total primary energy supply."
### Metrics:
Quantity of energy produced by each renewable source, measured in thousand tonne of oil equivalent (ktoe).
The percentage share of each renewable source in the total primary energy supply.
## Methodology
### Data Analysis:
- Calculate the annual contribution of each renewable energy source to the TPES.
* Analyze trends in renewable energy usage, identifying periods of significant growth or decline.
+ Further analysis can be conducted; the impact of technological, economic, and policy factors on renewable energy development.
### Tools and Techniques:
 Analyzing the location-based data on renewable energy usage from 1960 to 2015 with a focus on tools like Python, Azure Data Factory, Synapse Analytics, and Power BI.
- Data cleaning and preprocessing.
* Exploratory data analysis (EDA) to understand trends, patterns, and anomalies in the data.
   

# Prerequirement 
- Kaggle API Token
* Azure Subscription
+ Azure Data Lake Storage 
+ Azure Data Factory and Synapse Analysis workspace
* Power BI Desktop
## Setup
First inside the Azure CLI you need to connect Kaggle and pull the dataset. If you want quicker way you can:
- Download Renewable energy dataset from Kaggle
+ Upload it to Azure Data Lake storage

## Step by step 

1 CLI Bash comments:

mkdir -p ~/.kaggle
mv kaggle.json ~/.kaggle/kaggle.json
chmod 600 ~/.kaggle/kaggle.json




2
3
4
5


# End