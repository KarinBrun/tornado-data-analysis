# U.S. Tornado Data Analysis (1950–2025)

An analysis of historical U.S. tornado data exploring changes in tornado location, intensity, reporting, and human impact from 1950 through 2025.

This project uses Python for data preparation and analysis and Tableau for interactive data visualization.

## Project Overview

The goal of this project was to investigate long-term patterns in U.S. tornado activity using historical tornado records from NOAA.

The analysis focused on three primary research questions:

1. Is Tornado Alley shifting location?
2. Has tornado intensity changed over time?
3. Have advances in technology reduced the impact of tornadoes on people?

Rather than relying only on total tornado counts, the analysis compares geographic patterns, tornado strength, reporting trends, injuries, fatalities, and changes in tornado detection and classification.

## Project Links

- [Interactive Tableau Dashboard](https://public.tableau.com/views/Tornado_Dashboard/MainDashboard?:showVizHome=no&:device=desktop)
- [Prepared Dataset on Kaggle](https://www.kaggle.com/datasets/karinbrun/us-tornado-dataset-from-1950-to-2025)
- [Portfolio](https://karinbrun.name/)

## Technologies

- Python
- Jupyter Notebook
- Tableau
- NOAA tornado data
- Kaggle

## Data

The original tornado records were obtained from NOAA and cover tornado activity in the United States from 1950 through 2025.

I cleaned and prepared the data for analysis and published the resulting dataset on Kaggle so the prepared data can be reused and explored independently.

[View the prepared dataset on Kaggle](https://www.kaggle.com/datasets/karinbrun/us-tornado-dataset-from-1950-to-2025)

## Analysis

### 1. Is Tornado Alley Shifting Location?

The analysis compared tornado locations across decades using several approaches, including:

- Geographic distribution of EF1–EF5 tornadoes by decade
- Average reported tornado location by decade
- Locations of EF4–EF5 tornadoes
- Weak versus strong tornado reporting over time
- Changes between the Fujita and Enhanced Fujita rating systems

The average location of reported tornadoes shows some eastward movement, but the strongest tornadoes remain concentrated within the traditional Tornado Alley region. Increased detection and reporting of weaker tornadoes likely contributes to the apparent shift.

### 2. Has Tornado Intensity Changed Over Time?

Several measures were used to investigate changes in tornado intensity:

- Average tornado magnitude by year
- Percentage of tornadoes classified as EF3 or greater
- Annual EF5 tornado counts
- Differences between the Fujita and Enhanced Fujita rating systems

The data does not provide clear evidence that tornadoes have become consistently stronger or weaker. Improvements in weak-tornado detection and changes in the tornado rating system make long-term intensity comparisons more complicated.

### 3. Have Advances in Technology Reduced Tornado Impacts?

The analysis compared tornado-related injuries and fatalities over time while considering improvements in tornado detection and warning systems.

Tornado-related injuries generally declined as warning technology improved. Major outbreaks can still cause significant injuries and fatalities, but the overall trend suggests that advances in detection and warning systems have improved public safety.

## Key Findings

- Tornado Alley does not appear to have significantly shifted eastward based on the location of the strongest tornadoes.
- Reports of weaker tornadoes increased substantially as tornado detection technology improved.
- The data does not show clear evidence that tornadoes have become consistently stronger or weaker.
- EF5 tornadoes remain extremely rare.
- Tornado-related injuries have generally declined as warning and detection technology improved.
- Changes in tornado records reflect not only tornado activity, but also changes in detection, reporting, and classification.

## Limitations

Several factors should be considered when interpreting the results:

- The dataset covers 1950–2025, which is a limited period for evaluating long-term climate patterns.
- Tornado detection and reporting practices changed significantly throughout the study period.
- The transition from the Fujita Scale to the Enhanced Fujita Scale complicates direct comparisons of tornado intensity.
- The 2020s are an incomplete decade because the dataset currently ends in 2025.

## Repository Contents

```text
tornado-data-analysis/
├── .gitignore
├── README.md
└── tornado_analysis.ipynb
