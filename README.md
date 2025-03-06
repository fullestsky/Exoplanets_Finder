# Exoplanets_Finder
This project explores the dataset, and uses DL model to perform predictions

## Dataset https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data

### Dataset Summary: The Search for New Earths (Kepler Exoplanet Dataset) <br>

#### Overview <br>

This dataset originates from the NASA Kepler space telescope and records the change in flux (light intensity) of thousands of stars over time. The primary goal is to identify exoplanet-hosting stars by detecting periodic dimming, which suggests the presence of an orbiting planet. Each star is assigned a binary label:

**2 (Exoplanet-Star):** At least one confirmed exoplanet detected. <br>
**1 (Non-Exoplanet-Star):** No confirmed exoplanet detected. <br> <br>
The dataset has undergone preprocessing, with data mainly derived from Kepler’s Campaign 3 observations, complemented by exoplanet data from other campaigns to increase the number of positive cases.

#### Dataset Structure <br>
#### Train Set:

**Rows (Observations):** 5,087 stars <br>
**Columns (Features):** 3,198 flux values (time-series data) + 1 label column <br>
**Class Distribution:** <br> <br>
-37 Exoplanet-Stars <br>
-5,050 Non-Exoplanet-Stars <br>

#### Test Set:

**Rows (Observations):** 570 stars <br>
**Columns (Features):** 3,198 flux values (time-series data) + 1 label column <br>
**Class Distribution:** <br> <br>
-5 Exoplanet-Stars <br>
-565 Non-Exoplanet-Stars
