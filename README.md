# Red List Assessment & Population Prediction: Polar Bear

**Author:** Haoyang Qian (Lund University) **Assessing Experts:** Rouwen Xiao, Ullrika Sahlin

## Project Overview

This project is a quantitative assessment of the **Polar Bear** population status according to IUCN Red List categories. It utilizes a statistical approach to model the correlation between **sea ice decline** and population abundance, predicting future trends over three generations.

## Key Features

-   **Monte Carlo Simulation:** Conducted 1,000 simulations to estimate population changes based on variable sea ice data.

-   **Predictive Modeling:** Projects population abundance for the next three generations (approx. 33-45 years) starting from 2015.

-   **Uncertainty Analysis:** Establishes 95% confidence intervals (Upper: 0.15, Lower: -0.83) to determine the likelihood of population growth or decline.

-   **Expert Elicitation:** Incorporates independent expert judgment and confidence scoring (Average confidence: 5.5/10) to validate model results against IUCN criteria.

-   **Assessment Outcome:** The model indicates a high probability of population decline. Experts estimate a \~50% probability of "Least Concern" and \~23% for "Vulnerable".

## Tech Stack & Data

-   **Methods:** Linear Regression, Gamma Distribution Modeling, Monte Carlo Simulation.

-   **Data Source:**

    -   **Sea Ice Data:** Arctic daily sea ice extent (1979-2014).

    -   **Population Data:** IUCN Polar Bear Specialist Group (2015).

    -   **Reference:** [Sea Ice Projection Data](https://ningchenhui.github.io/Earth-Science/Sea-ice/esA0412/).

## Note

-   **Methodology:** Due to inaccessible core sea ice data from original studies, this project redefines `fitted.ice` values to reproduce assessments using alternative evaluation methods.

-   **Disclaimer:** This assessment serves as an academic reproduction and analysis for educational purposes. The confidence level is moderate due to data limitations.
