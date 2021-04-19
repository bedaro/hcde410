# HCDE410SP21 - A1

Files for HCDE410SP21 - Assigment A1

Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

This project demonstrates basic data analysis and documentation by using open
data from the Seattle Data API. This data is made available at
https://data.seattle.gov under license: https://data.seattle.gov/stories/s/Data-Policy/6ukr-wvup/

## Burke-Gilman_commuter_traffic.ipynb

This file analyzes the 2019 counts for bike and pedestrian traffic at NE
70th St on the Burke-Gilman Trail. Data source:
https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bicycle-and/2z5v-ecg8

This generates the file bg_traffic_bike_ped_2019.csv which contains the total
traffic at each hour in 2019 broken down by type (bike vs pedestrian) and
direction of travel. A plot of this data is also generated as
bg_traffic_bike_ped_2019.png.

## SODA_API_demo.ipynb

This file makes queries against the Socrata Open Data API (SODA)
documented at https://dev.socrata.com/ Specifically, the building permit
dataset (https://data.seattle.gov/Permitting/Building-Permits/76t5-zqzr) is
queried to look at how applications for construction of single-family homes
(SFRs), duplexes, and accessory dwelling units (ADUs) have changed over time.

This file produces the output files seattle_new_sfrs.csv,
seattle_new_duplexes.csv, and seattle_new_adus.csv. Each file contains columns
for permit number, class, application date, date of completion, and the permit
description. The queries rely on specific key words being in the decription in
specific order, and the matching is not incredibly accurate or heavily checked.
