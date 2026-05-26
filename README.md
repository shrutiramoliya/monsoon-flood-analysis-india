# Urban Flood Frequency Analysis in India (2010–2025)

## Project Overview

This project focuses on the exploratory analysis of urban flood events in India between 2010 and 2025. The study aims to understand temporal, spatial, and climate-related flood patterns using a structured flood-event dataset and exploratory data analysis (EDA) techniques.

The project investigates whether the frequency of urban floods in India has increased over time and examines possible relationships with climate and hydrological factors.

---

## Objectives

The main objectives of this project are:

- Analyze year-wise urban flood frequency trends in India
- Identify the most flood-affected states and cities
- Study month-wise and seasonal flood occurrence patterns
- Examine flood type distribution
- Explore possible climate influences such as ENSO phases
- Analyze antecedent rainfall characteristics associated with flood events

---

## Dataset Description

The dataset contains manually curated urban flood event records from 2010–2025 across major Indian cities and states.

### Dataset Variables

- DATE
- YEAR
- MONTH
- STATE
- CITY
- LATITUDE
- LONGITUDE
- FLOOD_EVENT_NAME
- FLOOD_TYPE
- KERALA_MONSOON_ONSET
- LOCAL_MONSOON_ONSET
- DAYS_AFTER_KERALA_ONSET
- ANTECEDENT_RAINFALL_MM
- EL_NINO
- LA_NINA
- ENSO_PHASE
- SOIL_MOISTURE
- DATA_SOURCE

---

## Data Sources

The dataset was compiled using multiple authoritative and publicly available sources including:

- India Meteorological Department (IMD)
- NOAA Climate Prediction Center
- National Disaster Management Authority (NDMA)
- ISRO Bhuvan / NRSC
- Disaster reports and verified news archives
- LatLong.net

A detailed Sources sheet is included inside the dataset workbook for transparency and reproducibility.

---

## Exploratory Data Analysis (EDA)

The EDA notebook includes:

- Dataset overview and inspection
- Missing value analysis
- Year-wise flood frequency analysis
- State-wise flood distribution
- City-wise flood distribution
- Month-wise flood occurrence analysis
- Flood type distribution
- ENSO phase analysis
- Antecedent rainfall analysis
- Data visualization and interpretation

---

## Tools and Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- VS Code
- GitHub

## Notebooks

### eda.ipynb
Exploratory analysis of urban flood frequency trends, affected regions, flood distribution, and temporal patterns.

### advanced_analysis.ipynb
Climate and relationship analysis exploring ENSO phases, antecedent rainfall, monsoon timing, and flood vulnerability patterns.

---

## Repository Structure

monsoon-flood-analysis-india/
│
├── data/
│   └── India_Flood_Dataset_Final.xlsx
│
├── notebooks/
│   ├── eda.ipynb
│   ├── advanced_analysis.ipynb
│   └── spatial_analysis.ipynb
│
├── requirements.txt
│
└── README.md
