# Dominos - Predictive Purchase Order System

## Project Overview

The **Dominos - Predictive Purchase Order System** aims to optimize the ingredient ordering process for Dominos by accurately forecasting future sales. By leveraging historical sales data and ingredient information, this project develops a predictive model to generate efficient purchase orders, minimizing waste and preventing stockouts.

## Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Business Use Cases](#business-use-cases)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Problem Statement

Dominos wants to optimize the process of ordering ingredients by predicting future sales and creating a purchase order. By accurately forecasting sales, Dominos can ensure that it has the right amount of ingredients in stock, minimizing waste and preventing stockouts.

## Business Use Cases

- **Inventory Management**: Ensuring optimal stock levels to meet future demand without overstocking.
- **Cost Reduction**: Minimizing waste and reducing costs associated with expired or excess inventory.
- **Sales Forecasting**: Accurately predicting sales trends to inform business strategies and promotions.
- **Supply Chain Optimization**: Streamlining the ordering process to align with predicted sales and avoid disruptions.

## Approach

1. **Data Preprocessing and Exploration**:
   - Data cleaning and handling missing values.
   - Exploratory Data Analysis (EDA) to identify trends and patterns.

2. **Sales Prediction**:
   - Feature engineering to create relevant features.
   - Model selection and training using time series forecasting models (e.g., ARIMA, Prophet).
   - Model evaluation using metrics like Mean Absolute Percentage Error (MAPE).

3. **Purchase Order Generation**:
   - Predicting sales for the next week.
   - Calculating required quantities of each ingredient based on predicted sales.
   - Generating a detailed purchase order.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Prophet
- Scikit-learn

## Dataset

- **Sales Data**: Historical sales records (Date, Pizza Type, Quantity Sold, Price, Category, Ingredients).
- **Ingredient Data**: Ingredient requirements for each pizza type (Pizza Type, Ingredient, Quantity Needed).

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn statsmodels prophet scikit-learn
