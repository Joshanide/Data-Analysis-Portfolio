# River Water Quality Indicators

## Dataset
These visualizations use environmental monitoring data collected at multiple river sampling sites in 2016. The dataset includes measurements of heavy metal concentrations and dissolved oxygen levels, along with corresponding water quality guideline thresholds.

[River Water Quality Measurements 1D5V Tableau 1.csv](https://github.com/user-attachments/files/24839827/River.Water.Quality.Measurements.1D5V.Tableau.1.csv)

## Analysis Focus
I was interested in understanding how metal concentrations vary along the river and whether certain locations consistently show higher levels than others. 

## Visualizations

### Heavy Metal Concentrations at River Sites (2016)
This bar chart shows measured concentrations of various heavy metals at different river sampling sites in 2016.

An average upper guideline value for copper is included as a reference line. This allows exceedances to be identified visually without requiring precise numeric interpretation. The chart highlights that copper levels exceed the guideline at multiple sites, while other metals generally remain below their respective thresholds.

<img width="1004" height="774" alt="heavyMetalsConcentrations" src="https://github.com/user-attachments/assets/eb3bcb18-7d09-4dc0-a921-c663daf21848" />

### Dissolved Oxygen Levels by Site (2016)
This line chart displays dissolved oxygen measurements across river sites over time in 2016.

A lower guideline threshold is included to provide context for interpretation. All observed values remain above this guideline, indicating consistent compliance for dissolved oxygen during the measured period.
<img width="1423" height="774" alt="dissolvedOxygenLevels" src="https://github.com/user-attachments/assets/440240e5-c9f8-4c73-9e9b-6346436851b7" />

### Water Quality Guideline Compliance Overview
This summary visualization presents guideline compliance by site and variable using a binary indicator.

A calculated field was used to mark each site-variable combination as either within guidelines or exceeding guidelines. This allows overall compliance patterns to be assessed at a glance, without requiring detailed inspection of individual measurements.

This view is intentionally high-level and complements the more detailed charts by emphasizing pattern recognition over precision.

<img width="956" height="521" alt="waterQualityComplianceBySiteAndVar" src="https://github.com/user-attachments/assets/61b5cf02-231f-44a7-aab3-5535457d9af2" />

## Notes on Interpretation
These visuals are exploratory and intended for comparison across sites and variables. Guideline values are included for reference only and should not be interpreted as formal compliance assessments.
