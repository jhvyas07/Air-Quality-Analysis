# Air Quality Analysis: Visualising Air and the Pollutants it Contains

## Project Overview

This project analyzes global air quality patterns using comprehensive data from OpenAQ, focusing on understanding how urban activities, temporal dynamics, and seasonal variations affect air pollution levels. Through interactive data visualizations created in Tableau, we explore three key hypotheses about air quality patterns in urban environments.

**Course:** DS612: Interactive Data Visualization  
**Institution:** Dhirubhai Ambani University  
**Team:** Group 11

- Jalak Vyas (202418062)
- Vedant Dave (202418014)
- Kumar Sanskar (202418027)
- Saarthak Jindal (202418046)

## Research Hypotheses

### Hypothesis 1: Major Cities vs. Smaller Towns

**Objective:** Assess whether major cities have higher pollution levels than smaller towns and if pollution accumulates over the day.

**Key Findings:**

- Sub-urban locations show lower averages and tighter interquartile ranges, indicating cleaner and more consistent air quality
- Urban areas have lower `O₃` concentrations due to `NO` reacting with ozone in high-traffic zones

### Hypothesis 2: Seasonal Variations in Air Quality

**Objective:** Investigate long-term exposure risks and climate effects on air quality.

**Key Findings:**

- All pollutants significantly decrease during rainy season
- Carbon Monoxide (`CO`) is less affected by rain compared to `PM10` and `PM2.5`
- Significant pollution dip during 2020-2022 due to COVID-19, especially in `NO₂` levels from reduced vehicle emissions

### Hypothesis 3: Traffic and Urban Activity Drive Rush Hour Peaks

**Objective:** Check if pollution levels peak during morning and evening commute times.

**Key Findings:**

- European cities (London & Paris) show similar patterns with pollution spikes during peak commute times (7-12 AM and 5-9 PM)
- Weekdays show significantly higher pollution levels than weekends
- Weekend pollution spikes occur during late evening hours when people go out

<!-- ## 📁 Project Structure

```
├── Presentation.pptx
├── Report.pdf
├── Dataset/
│   └── OpenAQ.rar
└── Tableau Worksheets/
    ├── H1&H3 SUBMISSION.twbx
    ├── H2 SUBMISSION.twbx
    └── H2p1.twbx
``` -->

## Dataset Description

**Source:** OpenAQ - A non-profit open-source project collecting global air quality data

**Key Pollutants Measured:**

- `PM2.5` (Fine Particulate Matter)
- `PM10` (Coarse Particulate Matter)
- `NO₂` (Nitrogen Dioxide)
- `SO₂` (Sulfur Dioxide)
- `CO` (Carbon Monoxide)
- `O₃` (Ozone)

**Dataset Attributes:**

- **Location:** Monitoring station name
- **City:** City where measurement was taken
- **Country:** Country of origin (ISO format)
- **Parameter:** Pollutant measured
- **Value:** Pollutant concentration
- **Unit:** Measurement unit (typically μg/m³)
- **Datetime:** UTC timestamp
- **Latitude/Longitude:** Geographic coordinates

## Tools and Technologies

- **Tableau:** Primary visualization and dashboard creation tool
- **OpenAQ API:** Data source for real-time air quality measurements
- **Data Processing:** Temporal feature extraction (hour, day, month, season)
- **Statistical Analysis:** Comparative analysis across urban/suburban areas

## Key Visualizations

### Urban vs. Suburban Pollution Analysis

- Comparative pollution density maps for London county
- Box plots showing pollution distribution by area type
- Scatter plots demonstrating concentration differences

### Temporal Pattern Analysis

- Hourly pollution trends for major European cities
- Weekday vs. weekend pollution comparison
- Rush hour peak identification visualizations

### Seasonal Variation Studies

- Multi-year pollution trends showing COVID-19 impact
- Seasonal pollution patterns by pollutant type
- Monthly heatmaps of pollution levels

## Methodology

1. **Data Preprocessing:**

   - Temporal feature extraction (hour, day, month, season)
   - Urban/suburban area classification
   - Data aggregation by time periods and locations

2. **Statistical Analysis:**

   - Hourly pollution averaging
   - Seasonal trend analysis
   - Comparative analysis between urban and suburban areas

3. **Visualization Design:**
   - Applied "What-Why-How" framework
   - Used appropriate marks (points, lines, areas) and channels (color, position)
   - Implemented interactive filtering and highlighting

## Key Insights

- **Urban Impact:** Sub-urban areas consistently show cleaner air with lower pollution variability
- **Temporal Patterns:** Clear pollution peaks during rush hours (7-12 AM, 5-9 PM) on weekdays
- **Seasonal Effects:** Rainy seasons significantly reduce particulate matter pollution
- **COVID-19 Impact:** Dramatic reduction in `NO₂` levels during 2020-2022 due to reduced traffic
- **Weekend Patterns:** Lower overall pollution with different peak timing patterns

## Learning Outcomes

This project demonstrates proficiency in:

- **Data Abstraction:** Mapping real-world air quality data to visualization-ready formats
- **Visual Encoding:** Effective use of marks and channels for different data types
- **Interactive Design:** Implementation of filtering, brushing, and highlighting techniques
- **Storytelling with Data:** Creating compelling narratives through visualization
- **Evaluation and Critique:** Applying visualization effectiveness principles

## How to Use This Repository

1. **View the Analysis:** Start with `Report.pdf` for comprehensive findings and methodology
2. **Explore Visualizations:** Open the Tableau workbooks (.twbx files) in Tableau Desktop or Tableau Public
3. **Understand Context:** Review the presentation slides for project overview at `Presentation.pptx`
4. **Access Data:** Extract the OpenAQ dataset for independent analysis

## Data Source Citation

Data sourced from [OpenAQ](https://openaq.org/) - a non-profit organization providing open access to real-time and historical air quality data from government and research institutions worldwide.

## Environmental Impact

This analysis contributes to understanding urban air pollution patterns, which is crucial for:

- Public health policy development
- Urban planning decisions
- Environmental monitoring strategies
- Climate change mitigation efforts

According to WHO, air pollution is responsible for millions of deaths annually, making this type of analysis essential for informed environmental and health policies.

---

_This project was completed as part of the Interactive Data Visualization course at Dhirubhai Ambani University, demonstrating the power of data visualization in understanding complex environmental challenges._
