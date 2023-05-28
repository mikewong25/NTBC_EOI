# NTBC Ecological Observation Inventory Dashboard

## Introduction
As part of the BCIT GIS Advanced Diploma program I completed a project for the Nature Trust of BC (NTBC). The product I created for NTBC is called the Ecological Observation Inventory Analysis (EOIA) and it is a colletion of scripts that compile and analyze ecological observation data. The project involved gathering ecological occurrence data from publicly available sources and completing analysis on the data to create summary tables and statistics of ecological occurrence data for each NTBC conservation property. The summary tables and statistics are meant to assist and inform conservation planning at NTBC. The NTBC Ecological Observation Inventory Dashboard showcases a portion of the final outputs produced from the project. 

### Project Statement, via NTBC
With input from NTBC staff, the student will compile a spatial database of ecological occurrence data available at a provincial scale. The student will also develop processes to produce different types of summary statistic outputs for use by NTBC staff in conservation planning. It is important to ensure that the methods are well documented and repeatable, ideally confined to a model or script created using ArcGIS Model Builder or ArcPy.

### Purpose of the Dashboard
The dashboard provides visualization of, and dynamic statistics for, the "Summary by Property Acquisition Number", which is one of the summary outputs created by the EOIA. The dashboard has been designed to highlight observations of species that are on BC's Red List. Species on the Red List include any species or ecosystem that is at risk of being lost (extirpated, endangered or threatened). The dashboard clearly displays information about the species at risk that have been observed in each NTBC conservation property.

## About the App

![AboutApp_01_Map](./EOIA_01_Map.png)

### The Map
The map displays ecological observation data as well as conservation property data. The legend below describes the sybmology of the data and can be accessed on the map itself by clicking the middle "list/legend" button in the top right of the map area.

![AboutApp_02_Legend](./EOIA_02_Legend.png)

The default view of the map is set to an overview of BC. The map also has preset bookmarks for easy navigation around BC, which can be accessed via the "ribbon/bookmark" button in the top right of the map area.

![AboutApp_03_Bookmarks](./EOIA_03_Bookmarks.png)

### Dynamic Statistics
The Dashboard provides dynamic statistics based on the information currently visible in the map frame. Statistics are provided for the following data:
- Observation Event Count: count of observation events visible on the map frame for "All Species" and for "Red List Species"
- Unique Species Count: count of unique species observed on the map frame for "All Species" and for "Red List Species"
- Conservation Area: the sum of the property and buffer areas visible on the map frame, in hectares.
- BC Red List Species: list of BC Red List Species observed on the map frame.

![AboutApp_04_Stats](./EOIA_04_Stats.png)

### Tables

![AboutApp_05_Tables](./EOIA_05_Tables.png)

## Data Dictionary
| <b>Dataset</b> | <b>Data Source</b> | <b>Data Type</b>
| --- | --- | --- |
| NTBC Properties | NTBC | Polygon |
| BC Species list | <a href="https://a100.gov.bc.ca/pub/eswp/search.do?method=reset">BC Species & Ecosystems Explorer</a> | Table |
| eBird Basic Dataset (S02_EBD) | <a href="https://support.ebird.org/en/support/solutions/articles/48000838205-download-ebird-data">eBird</a> | Point |
| iNaturalist Observations | <a href="https://inaturalist.ca/home">iNaturalist</a> | Point |
| SPI Masked Survey Observations - Publicly Available | <a href="https://catalogue.data.gov.bc.ca/dataset/wildlife-species-inventory-masked-survey-observations-publicly-available">BC Data Catalogue</a> | Polygon |
| SPI Survey Observations - Non-Sensitive | <a href="https://catalogue.data.gov.bc.ca/dataset/wildlife-species-inventory-survey-observations-non-sensitive">BC Data Catalogue</a> | Point |
| SPI Masked Feature Observations - Publicly Available | <a href="https://catalogue.data.gov.bc.ca/dataset/wildlife-species-inventory-masked-feature-observations-publicly-available">BC Data Catalogue</a> | Polygon |
| SPI Feature Observations - Non-Sensitive (Wildlife Habitat Features - FRPA) | <a href="https://catalogue.data.gov.bc.ca/dataset/wildlife-habitat-features-frpa">BC Data Catalogue</a> | Point |
| SPI Incidental Observations - Non-Secured | <a href="https://catalogue.data.gov.bc.ca/dataset/wildlife-species-inventory-incidental-observations-non-secured">BC Data Catalogue</a> | Point |
| SPI Telemetry Observations - Non-Sensitive | <a href="https://catalogue.data.gov.bc.ca/dataset/wildlife-species-inventory-telemetry-observations-non-sensitive">BC Data Catalogue</a> | Point |
| CDC Element Occurrences: Species and Ecosystems at Risk - Publicly Available Occurrences | <a href="https://catalogue.data.gov.bc.ca/dataset/species-and-ecosystems-at-risk-publicly-available-occurrences-cdc">BC Data Catalogue</a> | Polygon |
| CDC Element Occurrences: Species and Ecosystems at Risk (Masked Secured) | <a href="https://catalogue.data.gov.bc.ca/dataset/species-and-ecosystems-at-risk-masked-secured-publicly-available-occurrences-cdc">BC Data Catalogue</a> | Polygon |


## Links
<a href="https://www.naturetrust.bc.ca/">Nature Trust of British Columbia</a>
<a href="https://www.bcit.ca/programs/geographic-information-systems/">BCIT GIS</a>
<a href="https://www.linkedin.com/in/michael-wong-526098214/">Michael Wong - LinkedIn</a>

