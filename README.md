# Impact of Natural Disasters on Regional Unemployment in the Philippines

## Overview

This project investigates the relationship between natural disasters and unemployment rates in the Philippines. Using official labor force statistics from the Philippine Statistics Authority (PSA) and historical disaster event records from the EM-DAT Philippines dataset and analyze data for regional trend analysis.

The project aims to answer the following research question:

**Do natural disasters contribute to higher unemployment rates in affected Philippine regions?**

---

## Data Sources

### 1. Philippine Statistics Authority (PSA) - Labor Force Survey

Official labor force statistics containing employment, unemployment, and underemployment rates.

**Dataset Source:**

* https://psa.gov.ph/statistics/labor-force-survey
* https://openstat.psa.gov.ph

**Key Fields:**

* Region
* Year
* Month
* Employment Rate
* Unemployment Rate
* Underemployment Rate
* Labor Force Participation Rate

---

### 2. EM-DAT Philippines Geocoded Disaster Dataset

Historical disaster event records containing disaster locations, affected populations, deaths, and economic damages.

**Dataset Source:**

* https://www.aiddata.org/data/em-dat-phl

**Available Files:**

* disasters.csv
* locations.csv
* disasters_locations_merged.csv
* data_dictionary.csv

**Key Fields:**

* disaster_id
* disaster_type
* year
* month
* province
* municipality
* deaths
* affected
* damages

---

## Project Objectives

* Extract labor force statistics from PSA datasets.
* Extract disaster event records from EM-DAT.
* Standardize geographic information across datasets.
* Aggregate disaster statistics by region and year.
* Store processed data in a centralized data warehouse.
* Analyze correlations between disasters and unemployment rates.
* Build interactive dashboards and reports.

---
