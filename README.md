# Octopoda Biodiversity Analysis

Global analysis of Octopoda occurrence records using OBIS data, Python, K-Means clustering, sea surface temperature (SST) trend modelling and Power BI.

## Project Overview

This project explores global Octopoda occurrence patterns and their environmental context using public biodiversity data from the Ocean Biodiversity Information System (OBIS).

The project follows an end-to-end data science workflow covering data cleaning, exploratory data analysis, spatial feature engineering, K-Means clustering, cluster validation, SST trend modelling, environmental relationship analysis and interactive Power BI visualisation.

Because the occurrence records are distributed globally, latitude and longitude were transformed into three-dimensional spherical coordinates before K-Means clustering. This reduces the distortion caused by treating the Earth as a flat two-dimensional surface.

The analysis is exploratory. OBIS occurrence records represent where organisms have been recorded and should not be interpreted as direct evidence of population abundance, migration or causal ecological change.

## Analytical Workflow

![End-to-end analytical workflow](assets/workflow/analytical-workflow.png)

The workflow combines public biodiversity data, Python-based ETL and modelling, and Power BI reporting to move from raw occurrence records to geographical clustering, environmental trend analysis and interactive visualisation.