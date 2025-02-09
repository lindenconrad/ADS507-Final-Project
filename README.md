# ADS507-Final-Project

# Air Quality & Health Impact Analysis 🚀

## Project Overview 📌
This project analyzes the impact of air pollution on public health, specifically in Southern California counties. The datasets include air quality measurements, emergency department visits, and hospitalizations related to asthma. The data was imported into an Azure MySQL database for further analysis.  The data pipeline integrates air quality data from the <website> with health records to study pollution exposure effects on health outcomes.

# Database Structure 🗂️
The project uses MySQL (hosted on Azure) for data storage and processing.

These tables contain data related to air pollution levels, air quality index (AQI), and asthma-related emergency and hospitalization cases.

The database consists of multiple tables containing pollution data and health data:

| Table Name                          | Description             |
|-------------------------------------|-------------------------|
| `ad_viz_plotval_data_1`             | PM2.5 pollution data    |
| `ad_viz_plotval_data_2`             | CO pollution data       |
| `ad_viz_plotval_data_4`             | PM2.5 pollution data    |
| `ad_viz_plotval_data_10`            | CO pollution data       |
| `ad_viz_plotval_data_11`    	      | PM2.5 pollution data    |
| `ad_viz_plotval_data_6`             | CO pollution data       |
| `ad_viz_plotval_data_8`             | PM2.5 pollution data    |
| `ad_viz_plotval_data_9`             | CO pollution data       |
| 'asthma-emergency-2015_2022'        | asthma ER visits        |
| 'asthma-hospitalization-2015_2022'  | Asthma hospitalizations |

The pollution data were combined into one table, health data combined into another table, and one final table was created.


### Database: `air_quality_analysis`




### Data Processing and Analysis

The data is structured and stored in MySQL for efficient querying and analysis.

Queries were written to merge datasets and extract relevant insights.

Further analysis and visualization will be performed using Python in a Jupyter Notebook environment.



### Next Steps





### Contributors:
Linden Conrad-Marut, Marinela Inguito, Liam Richardson
Organization: University of San Diego

---
