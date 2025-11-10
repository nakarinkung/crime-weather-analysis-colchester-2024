# Crime and Weather Analysis in Colchester (2024)
A comprehensive analysis of crime patterns and their relationship with weather conditions in Colchester during 2024. This project combines police crime data with meteorological measurements to identify patterns, trends, and insights that could inform policing strategies and community safety measures.

## Project Overview
This analysis examines:

1. Crime distribution across different categories and locations
2. Seasonal patterns in criminal activity
3. Weather influences on crime rates (temperature, precipitation, wind)
4. Geospatial hotspots of criminal activity
5. Correlation analysis between environmental factors and crime

## Key Findings
**Crime Distribution**

-**Violent crime** dominated with 2,420 incidents (38.4% of total)

-**Top 5 crimes**: Violent crime, Anti-social behaviour, Shoplifting, Criminal damage & arson, Public order offences

**Seasonal variations**: Anti-social behaviour peaks in spring, shoplifting increases in autumn/winter

---

**Weather Correlations**

**Temperature**: Moderate positive correlation with crime (r = 0.42)

**Precipitation**: Strongest correlation with crime (r = 0.58)

**Wind speed**: Negative correlation (r = -0.45), potentially disruptive to criminal activity

**Humidity**: Minimal correlation (r = -0.08)

---

**Hotspot Locations**

Supermarkets: 505 incidents (highest concentration)

Shopping areas: 458 incidents

Nightclubs: 207 incidents

Areas near police stations and parking lots


## Required R Packages

"tidyverse",
  "lubridate",
  "leaflet",
  "corrplot",
  "viridis",
  "kableExtra",
  "ggplot2",
  "dplyr",
  "xts",
  "plotly"

---

## Data Files
crime24.csv - Police crime data

temp24.csv - Meteorological data

---

## Visualisations Included
**Pie Chart**: Crime category proportions

**Bar Plots**: Top crimes and seasonal patterns

**Time Series**: Daily temperature and monthly crime trends

**Box Plots**: Temperature and wind speed distributions

**Scatter Plots**: Weather variables vs. crime counts

**Correlation Matrix**: Weather-crime relationships

**Interactive Map**: Crime hotspots using Leaflet

**Smoothed Time Series**: Crime trends by category

---

## Key Insights for Law Enforcement

**Strategic Recommendations**

**Seasonal Resource Allocation**: Increase patrols in retail areas before holidays

**Weather-Responsive Deployment**: Enhanced monitoring during warm, rainy periods

**Hotspot Targeting**: Focus resources on supermarkets, shopping areas, and nightlife districts

**Preventive Measures**: Improve lighting and CCTV in identified high-risk zones

---

**Crime Prevention Opportunities**

**Summer**: Address vehicle crime and public order offences

**Autumn/Winter**: Target shoplifting and theft-related crimes

**Spring**: Monitor anti-social behaviour hotspots

**Year-round**: Maintain focus on violent crime reduction
