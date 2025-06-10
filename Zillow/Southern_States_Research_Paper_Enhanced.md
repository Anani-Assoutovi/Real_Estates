# Socioeconomic Disparities in Southern U.S. States

**Author:** Anani A. Assoutovi  
**Affiliation:** Independent Researcher / Data Scientist  
**Email:** booking.helices4s@icloud.com  
**LinkedIn:** www.linkedin.com/in/ananiassoutovi  
**Date:** June 10, 2025  

---

## Abstract

This research investigates economic and social trends across U.S. southern states, focusing on disparities in median income, poverty rates, and education. Public census data and visualization tools are used to reveal structural patterns and inform policy-relevant insights. The findings highlight persistent inequality across the region.

---

## 1. Introduction

The southern region of the United States has historically experienced uneven economic development and persistent poverty. This study examines quantitative indicators such as income and poverty levels to analyze inter-state variations and inform socioeconomic planning.

---

## 2. Dataset

- **Source**: U.S. Census Bureau and American Community Survey (ACS)
- **Scope**: Southern states (e.g., Mississippi, Alabama, Texas, Georgia, etc.)
- **Variables**: Median household income, poverty rates, education level

---

## 3. Methodology

### 3.1 Data Acquisition and Cleaning

- Public datasets were downloaded from the U.S. Census portals
- Converted CSV formats to pandas dataframes
- Removed or handled missing values

### 3.2 Analytical Methods and Types of Analysis

- **Descriptive Statistics**: Computed means, medians, and ranges for each variable
- **Comparative Analysis**: Compared metrics across different states to identify disparities
- **Geospatial Analysis**: Visualized regional income variations using county-level maps
- **Correlation Analysis**: Explored relationships between income, poverty, and education
- **Clustering (Optional)**: Identified regions with similar socioeconomic profiles
- Aggregated income and poverty levels by state
- Mapped geospatial distribution of income using choropleths

### 3.3 Visualization Tools

- **Bar Plots**: To compare state-wise income and poverty levels
- **Geospatial Maps**: Visualized income across counties
- **Heatmaps**: To detect clustering of low/high-income regions

---

## 4. Findings

- **Median Income**: States like Mississippi and Louisiana consistently rank at the bottom.
- **Poverty Rates**: Higher-than-average poverty was observed in rural and historically marginalized areas.
- **Geospatial Patterns**: Distinct income disparities exist between urban and rural counties.
- These disparities suggest entrenched systemic issues, potentially tied to education access and employment opportunities.

---

## 5. Conclusion

The analysis provides evidence of significant socioeconomic disparities in southern U.S. states. It emphasizes the need for targeted intervention strategies and equitable distribution of public resources. Geospatial trends suggest a strong urban-rural divide that should guide infrastructure and welfare planning.

---

## 6. Future Work

- Incorporate health and housing metrics for a multidimensional poverty index
- Use time-series data to observe income mobility over the years
- Deploy machine learning models to predict future income shifts

---

## References

- U.S. Census Bureau: https://www.census.gov/
- pandas, geopandas, seaborn, matplotlib libraries
- American Community Survey (ACS)
