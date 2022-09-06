# NYC Coronavirus Disease 2019 (COVID-19) Data   

[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://ourworldindata.org/coronavirus)
[![Data](https://img.shields.io/badge/go_to-data-purple)](public/data/)
[![documentation](https://img.shields.io/badge/go_to-dev_docs-0055ff)](https://docs.owid.io/projects/covid)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Introduction

**📢 This repository contains data on Coronavirus Disease 2019 (COVID-19) in New York City (NYC). The Health Department classifies the start of the COVID-19 outbreak in NYC as the date of the first laboratory-confirmed case, February 29, 2020.**
  
The purpose of this project is to introduce a useful online interactive dashboard that visualize and follow confirmed cases of COVID-19 in New York City. The dashboard illustrates the counts of confirmed cases, deaths, and recoveries of COVID-19. This dashboard is user-friendly and is built in open-source R software (Shiny in particular); ensuring a high sense of transparency and reproducibility.

## How to use this repository
This repository contains CSV (comma separated values) files of data, and Readme files with important documentation of the data. If you are unfamiliar with Github, you may find these instructions helpful:

**To download data**, scroll up to the green button labelled "Code." Clicking this button will start a download of a ZIP file of the entire contents of this repository.

Alternatively, you can download a single file. Click on a file you would like to download. Next, click the "Raw" button. Right click and save as a CSV file. 

**For help understanding a file**, you can consult the documentation we have provided in the Readme files for each folder of data. To find  Readme files, just click on a folder name, above, and scroll down. Documentation is organized by file name, so you can scroll through the Readme, find the name of the file you are using for, and read documentation on it. Additionally, some universal documentation is provided in the [Key Technical Notes](https://github.com/nychealth/coronavirus-data/blob/master/README.md#key-technical-notes). 

**Questions and custom requests**: We will try to answer questions about the data in this repository as we are able to. If you have a question, please search the [Issues](https://github.com/nychealth/coronavirus-data/issues?q=) to see if it’s already been addressed. Please understand that we are responding to a pandemic and we might not be able to address all questions in a timely manner.  We are not able to accommodate custom data requests placed via Github.  


| Prior file name(s) | New file name(s) | New file location | 
|----------------------------------------------------------------|--------------------------------------------------------------------------|-------------------| 
| boro.csv | by-boro.csv | Totals/ | 
| case-hosp-death.csv | data-by-day.csv | Trends/ | 
| tests-by-zcta | data-by-modzcta.csv | Totals/ | 
| boro/boroughs-case-hosp-death.csv | data-by-day.csv | Trends/ | 
| boroughs-by-age.csv, boroughs-by-race.csv, boroughs-by-sex.csv | group-data-by-boro.csv, group-case-by-boro.csv, group-hosp-by-boro,csv, group-deaths-by-boro.csv | Totals/ | 
| deaths/probable-confirmed-dod.csv | data-by-day.csv | Trends/ | 
| sydromic_data.csv | covid-like-illness.csv | Trends/ | 
| recent-4-week-citywide.csv | Similar data available in now-summary.csv | Latest/ | 
| recent-4-week-by-modzcta.csv | Similar data available in caserate-by-modzcta.csv, testrate-by-modzcta.csv, percentpositive-by-modzcta.csv | Trends/ | 

### 

***
