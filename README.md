# Country Data Analysis

## Project Overview

This project focuses on the comprehensive analysis of country-level data to uncover insights related to global trends, well-being, and socio-economic factors. By leveraging various machine learning techniques, the project aims to identify inherent patterns, classify countries, and predict key indicators.

## Data Collection

The initial dataset was compiled using Microsoft Excel's Copilot feature, specifically utilizing its "Geography" data type and associated formulas to gather relevant country information. The raw data was then further processed and cleaned for analytical use.

## Analysis Performed

The project employs a multi-faceted analytical approach, as detailed in the respective Jupyter notebooks:

-   **Exploratory Data Analysis (EDA):** Conducted to understand data distributions, identify relationships between variables, and prepare the data for modeling. (See `EDA/eda.ipynb`)
-   **Regression Analysis:** Utilized for predictive modeling of continuous outcomes, aiming to understand the factors influencing various country-specific metrics. (See `MODEL/regression.ipynb`)
-   **Classification:** Applied to categorize countries into predefined groups or classes based on their features. (See `MODEL/classification.ipynb`)
-   **Clustering (Unsupervised Learning):** Employed to group similar countries together, revealing natural groupings and structures within the dataset without prior labels. This helped in identifying country clusters. (See `MODEL/Unsupervised.ipynb`)
-   **Anomaly Detection:** Techniques were also applied to identify unusual data points or outliers that might represent unique country characteristics or data inconsistencies.

## Outputs and Reporting

-   **Cleaned Data:** Processed and cleaned datasets are stored in the `Data/` directory (e.g., `countries_clean.csv`, `country_data_cleaned.xlsx`).
-   **Visualizations:** Key findings and cluster formations are visualized in images such as `Global Synthesis Country Clusters.png` and `Global Wellbeing.png`.
-   **Reports:** The analyzed data was further utilized in Google NotebookLM to generate detailed reports and narratives based on the insights derived from this project.
-   **Reference Documents:** Supporting documents like `Anatomy_of_Nations.pdf` and `Global_Data_Atlas.pdf` provide additional context and information.

## Project Structure

-   `Data/`: Contains raw and cleaned datasets in various formats (CSV, Excel, pickle).
-   `EDA/`: Jupyter notebooks for Exploratory Data Analysis.
-   `MODEL/`: Jupyter notebooks for machine learning models (regression, classification, unsupervised learning).
-   `Anatomy_of_Nations.pdf`, `Global_Data_Atlas.pdf`: External reference documents.
-   `countries_cluster.xlsx`: Excel file potentially containing clustering results.
-   `Global Synthesis Country Clusters.png`, `Global Wellbeing.png`: Key visualization outputs.
