## Introduction

In recent years, drought has become a significant issue in the United States. Climate change and shifting precipitation patterns have increased the frequency and severity of drought conditions across many regions. Particularly in western states such as **California**, **Nevada**, **Arizona**, **New Mexico**, and **Colorado**, drought has raised serious concerns. These areas are facing decreasing water resources, agricultural challenges, and threats to natural ecosystems due to reduced rainfall and rising temperatures.

This project aims to analyze how drought conditions have affected various states across the United States over defined time periods.

---

## Dataset and Preprocessing

### Dataset Description

The dataset contains drought-related statistics for different U.S. states across multiple time periods. Each row includes the following variables:

| Variable | Type    | Description                         |
|----------|---------|-------------------------------------|
| 0        | Double  | Area Information                    |
| Date     | String  | Observation Date                    |
| D0       | Double  | Abnormally Dry                      |
| D1       | Double  | Moderate Drought                    |
| D2       | Double  | Severe Drought                      |
| D3       | Double  | Extreme Drought                     |
| D4       | Double  | Exceptional Drought                 |
| -9       | Double  | No Data                             |
| W0       | Double  | Abnormally Wet                      |
| W1       | Double  | Moderate Wet                        |
| W2       | Double  | Severe Wet                          |
| W3       | Double  | Extreme Wet                         |
| W4       | Double  | Exceptional Wet                     |
| state    | String  | U.S. State Name                     |

Before analysis, the dataset undergoes preprocessing to handle missing values and ensure the data is ready for modeling and visualization.

---

