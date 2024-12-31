# Analyzing a Decade of Crime: Insights from Chicago’s Criminal Incident Data (2013–2022)

**Author**: Linguo Ren  
**Date**: November 24, 2024  

---
## **Full Project Report**
https://rpubs.com/linguoren2001/1258923/

## **Introduction**
This project analyzes criminal incident data from the Chicago Police Department for the years 2013 to 2022. The dataset, comprising over 2.5 million records, includes detailed attributes such as date, location, crime type, arrest status, and more. By focusing on a decade of data, this analysis explores trends in crime, arrest ratios, and patterns across time and space.

---

## **Goals**
- **Crime Analysis**:
  - Understand temporal and spatial crime patterns in Chicago.
  - Explore variations in crime types and their prevalence across districts.
- **Arrest Analysis**:
  - Examine arrest ratios across different districts, crime types, and times of day.
  - Identify areas and times with significant disparities in arrest outcomes.
- **Statistical Validation**:
  - Use bootstrapping techniques to test the significance of observed trends.

---

## **Key Insights**
- **Crime Trends**: Crime rates have generally decreased since 2013, with a noticeable dip in 2020 during the COVID-19 pandemic. However, 2022 saw a slight uptick.
- **Arrest Ratios**: 
  - Prostitution, gambling, and narcotics exhibit high arrest ratios.
  - Theft and battery report consistently lower arrest ratios.
- **Temporal Patterns**:
  - Crimes peak around midnight and lunchtime.
  - Arrest ratios are highest in the evening, around 7–8 PM.
- **District Variations**:
  - Arrest ratios differ significantly between districts, reflecting disparities in enforcement priorities or resources.

---

## **Visualizations**
The repository contains various visualizations to enhance understanding:
1. **Heatmaps**:
   - Crime density across Chicago.
   - Arrest ratios by district, hour, and crime type.
2. **Line Graphs**:
   - Annual crime trends.
   - Hourly crime and arrest trends.
3. **Bar Charts**:
   - Comparison of crime counts and arrests across districts.
4. **Bootstrap Hypothesis Testing**:
   - Statistical validation of observed differences.

---

## **Methodology**
1. **Data Preparation**:
   - Filtered and cleaned data for the years 2013–2022.
   - Grouped by time, location, and crime attributes for focused analysis.
2. **Statistical Analysis**:
   - Conducted hypothesis testing using bootstrapping for arrest ratios by hour, district, and crime type.
3. **Visualization**:
   - Created heatmaps, line charts, and bar graphs to communicate insights effectively.

---

## **Challenges**
- **Dataset Size**: Managing over 2.5 million records required efficient sampling and computation.
- **Computational Overhead**: Bootstrapping led to frequent RStudio crashes, requiring optimized workflows.

---

## **Conclusion**
This project offers a deep dive into Chicago’s crime and arrest patterns, providing insights into:
- Temporal and spatial crime dynamics.
- Disparities in arrest ratios across districts and crime types.
- Statistically validated trends for better policymaking and resource allocation.

---

## **Acknowledgements**
- **Professor Jack O’Brien**  
- [Chicago Crime Dataset](https://www.kaggle.com/datasets/chicago/chicago-crime) by the Chicago Police Department  
- [Google Maps Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview)

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repository>.git
