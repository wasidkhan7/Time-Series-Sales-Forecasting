# Time-Series-Sales-Forecasting

## Overview
This project aims to forecast sales for a retail company using historical data. The project involves data preprocessing, exploratory data analysis (EDA), and the development of a predictive model.

## Table of Contents
1. [Project Description](#project-description)
2. [Dataset](#dataset)
3. [EDA](#eda)
4. [Modeling](#modeling)
5. [Results](#results)
6. [How to Use](#how-to-use)
7. [Technologies Used](#technologies-used)


## Project Description
Retail sales forecasting is crucial for inventory planning, resource allocation, and maximizing revenue. This project builds a forecasting model based on features such as product category, promotion status, and seasonal trends.

## Dataset
- **Source**:click for seeing dataset [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)
- **Features**:
  - `id`: Unique identifier for each entry.
  - `store_nbr`: Store number indicating the branch.
  - `family`: Product category.
  - `onpromotion`: Indicates whether the product is on promotion.
  - `year`, `month`, `day`: Date of sale. and more

## EDA
The exploratory data analysis provided insights into:
1. Seasonal sales trends.
2. Impact of promotions on sales.
3. Category-wise contribution to overall sales.
4. Store-level sales performance.

Key visualizations include:
- Line charts for sales trends.
- Bar charts for category-wise and store-wise performance.
- Correlation heatmaps to identify feature relationships.

## Modeling
A predictive model was trained by RandomForestRegressor using features such as:
- `store_nbr`, `family`, `onpromotion`, and temporal features (`year`, `month`, `day`).

### Model Used
- [ Random Forest Regressor]
- **Evaluation Metric**: r2_score 90%

## Results
The model achieved the following performance:
- **MAE**: [90%]
- The predictions align well with the historical trends and seasonal patterns observed during EDA.

## Technologies Used
### Programming Language: Python
### Libraries: pandas, NumPy, Matplotlib, Seaborn, scikit-learn
### Visualization Tools: Matplotlib, Seaborn
