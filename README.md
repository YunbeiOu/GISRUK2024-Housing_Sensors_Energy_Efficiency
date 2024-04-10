# Impact of Housing Energy Efficiency on Indoor Environment at the Overheating Summer

## Project Details

This study is part of the project of [Sensor Enhanced Housing Survey for Urban Heat Investigation](https://github.com/congying-hu/SensorEnhancedSurveyHeatInvestigation). Having collected indoor environment sensor measurement data,
this study aims to utilize sensor data to understand how the housing energy efficiency influence the indoor environment in the summer.

This project is a co-funded by Bureau of Investigative Journalism (TBIJ) and the University of Glasgow’s Urban Big Data Centre. 

## Paper
Research data, method and findings can be found in our GISRUK2024 conference paper: https://zenodo.org/records/10926876.

## Project Team

UBDC:

[Qunshan Zhao](https://www.gla.ac.uk/schools/socialpolitical/staff/qunshanzhao/); [Mark Livingston](https://www.gla.ac.uk/schools/socialpolitical/staff/marklivingston/); [Congying Hu](https://www.linkedin.com/in/congying-hu/); [Mingkang Wang](https://www.linkedin.com/in/mingkangwang-glasgow/); [Yunbei Ou](https://www.ubdc.ac.uk/about-ubdc/who-we-are/team-profiles/phd-students/yunbei-ou/)

TBIJ: 

[Rachel Hamada](https://www.thebureauinvestigates.com/profile/Rachelhamada); [Paul Eccles](https://www.thebureauinvestigates.com/profile/pauleccles)

## Data

There are three dataset in the data folder: [Household Indoor Sensor Measurement Data](data/Smart_Citizen_Data_concat), [SensorID_EPC_Survey_Open_Data](data/SensorID_EPC_Survey_Open_Data.csv), and [LIMBO (Weather Station) data](data/LIMBO.csv). 

### Household Indoor Sensor Measurement Data (Smart_Citizen_Data_Concat folder)
This folder includes a variety of environmental parameters captured by the [Smart Citizen Kits (SCK) sensors](https://smartcitizen.me/), such as air temperature, relative humidity, air quality, CO2 level, noise condition, and light condition.

### SensorID_EPC_Survey_Open_Data
This csv file includes the IDs of the sensors, selected survey data conducted by TBIJ, [IMD quintiles](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2019), and [existing Energy Performance Certificate (EPC) ratings](https://epc.opendatacommunities.org/).

### LIMBO (Weather Station) Data
This csv file contains outdoor weather observation data from the [Met Office](https://wow.metoffice.gov.uk/observations/details/20231207yr5eh6cw9ye67kyhyyguw39cda).

## Data Analysis Note

When generating the plots and conducting the analysis, we used the battery start charge time but delayed it by 1 hour (as participants were told to write down their start time 1 hour after charge) to allow the sensor to settle in the indoor environment and this helped improve the accuracy of indoor sensor measurements.
