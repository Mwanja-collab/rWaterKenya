# rWaterKenya

## Kenya Water Service Providers Performance Datasets (2023/2024–2024/2025)

`rWaterKenya` is an R package designed to make Kenya Water Service Providers (WSPs) performance data accessible to researchers, students, and analysts.

The package provides datasets covering water service provider performance in Kenya. These datasets support statistical exploration, academic research, and the analysis of water service delivery across different reporting periods.

## Installation

Install the development version from GitHub:

```r
install.packages("remotes")
remotes::install_github("Mwanja-collab/rWaterKenya")
```

## Available datasets

The package currently provides two datasets.

### 1. `water_data` – 2024/2025

This dataset contains performance information for 94 water service providers in Kenya for the 2024/2025 reporting period.

It includes variables relating to population served, water production, water consumption, non-revenue water, financial performance, staffing, and regulatory compliance.

Load the dataset using:

```r
library(rWaterKenya)

data("water_data")

head(water_data)
names(water_data)
str(water_data)
```

### 2. `water_panel_data` – 2023/2024 to 2024/2025

This dataset combines water service provider performance information for the 2023/2024 and 2024/2025 reporting periods.

It contains 184 provider-year observations representing 92 matched water service providers across the two reporting periods.

The dataset is organised in long format, with each provider represented by a separate observation for each year. It is suitable for examining changes in provider performance over time and conducting panel data analysis.

Load the panel dataset using:

```r
library(rWaterKenya)

data("water_panel_data")

head(water_panel_data)
dim(water_panel_data)
names(water_panel_data)
str(water_panel_data)
```

**Note:** Some variables have missing observations. Additionally, certain billed-volume variables are retained separately because their definitions differ between the two reporting periods. Users should consider these differences when conducting statistical analysis.

## Dataset DOI

The associated dataset record is available on Zenodo:

https://doi.org/10.5281/zenodo.23685035


## Author

**Calistus Mwanja**

GitHub: [Mwanja-collab](https://github.com/Mwanja-collab)

Email: callymwanja@gmail.com












