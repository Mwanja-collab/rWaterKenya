# rWaterKenya

## Kenya Water Service Providers Performance Dataset (2024/2025)

`rWaterKenya` is an R package designed to make the Kenya Water Service Providers Performance Dataset accessible to researchers, students, and analysts.

The dataset supports statistical exploration of water service provider performance and water service delivery in Kenya.

## Installation

Install the development version from GitHub:

```r
install.packages("remotes")
remotes::install_github("Mwanja-collab/rWaterKenya")
```

## Load the dataset

After installation, load the package and access the dataset:

```r
library(rWaterKenya)

data("water_data")

head(water_data)
names(water_data)
str(water_data)
```

## Dataset DOI

The associated dataset record is available on Zenodo:

https://doi.org/10.5281/zenodo.23685035

## Intended use

The dataset can support educational exercises, exploratory data analysis, statistical summaries, and research on water service delivery in Kenya.

## Author

Calistus Mwanja Nyongesa








