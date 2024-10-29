# Client Spending Analysis Project

## Overview

This project aims to analyze the factors influencing client spending in an online retail environment. Using a machine learning model, we investigate the relationships between various predictors, including the length of membership, time spent on the app, and time spent on the desktop website, to understand their impact on customer spending.

## Table of Contents

- [Project Goals](#project-goals)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Interpretation](#interpretation)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Project Goals

- Determine the significant factors influencing client spending.
- Compare the impact of mobile app usage against desktop website usage.
- Provide actionable insights for improving online marketing strategies.

## Data Description

The dataset includes the following features:
- **Client ID:** Unique identifier for each client.
- **Length of Membership:** Duration of the client's membership (in years).
- **Time Spent on App:** Total time spent on the mobile application (in minutes).
- **Time Spent on Desktop Website:** Total time spent on the desktop website (in minutes).
- **Amount Spent:** Total amount spent by the client (in currency).

## Methodology

1. **Data Preprocessing:** Clean and preprocess the data for analysis.
2. **Exploratory Data Analysis (EDA):** Visualize the relationships between predictors and the target variable (amount spent).
3. **Model Building:** Train a regression model to predict spending based on the selected features.
4. **Model Evaluation:** Assess model performance using metrics such as R-squared and Mean Absolute Error.

## Results

- The analysis indicates that the length of membership is the most significant predictor of client spending.
- Among the predictors, the app shows a much stronger influence on spending compared to the desktop website.
- There is minimal correlation between time spent on the desktop site and the amount spent.

## Interpretation

These findings suggest two possible interpretations:
1. The desktop website may need enhancements to better convert visitors into customers.
2. Consumers are likely more influenced by mobile applications than by desktop websites, indicating a potential area for marketing focus.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
https://github.com/SiddarthValas/Linear-Regression-Ecommerce-Customer-analysis-a

2.	Navigate into the project directory:
cd client-spending-analysis

3.	Install the required packages:
pip install -r requirements.txt

Usage

	1.	Load the dataset using your preferred method (e.g., Pandas).
	2.	Run the analysis scripts to generate insights and visualizations.
	3.	Review the results and consider recommendations for online marketing strategies.

Contributors

- Siddarth Valasubramanian

License

This project is licensed under the MIT License. See the LICENSE file for more details.
