# Dataset Overview

This repository houses three datasets that have been merged into a single, cohesive dataset to enable in-depth analysis and predictive modeling.
Below is a summary of each dataset and the purpose of the merged data:

## 1. Stores Dataset
- **File:** `stores_data_set.csv`
- **Description:** Contains metadata about retail stores, such as their size and classification.
- **Key Fields:**  
  - `Store`: Unique identifier for each store.  
  - `Type`: Category or type of store (e.g., A, B, C).  
  - `Size`: Physical size of the store.

## 2. Sales Dataset
- **File:** `sales_data_set.csv`
- **Description:** Weekly sales information for various departments across different stores.  
- **Key Fields:**  
  - `Store`: Matches the store ID in the Stores dataset.  
  - `Dept`: Identifier for store departments.  
  - `Date`: Week of the sale.  
  - `Weekly_Sales`: Sales figures for that week.  

## 3. Features Dataset
- **File:** `features_data_set.csv`
- **Description:** External factors that could influence sales, such as weather and economic indicators.  
- **Key Fields:**  
  - `Store`: Matches the store ID in the Stores dataset.  
  - `Date`: Matches the week of sales in the Sales dataset.  
  - `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`: Factors affecting store performance.

## Merged Dataset
The datasets are merged using **Store** and **Date** as the primary keys to create a unified dataset. This enables comprehensive analysis by integrating store details, weekly sales, and external influencing factors.  

### Key Features of the Merged Dataset
- Combines store-specific information with weekly sales and external features.
- Facilitates correlation analysis between sales and external factors.
- Enables predictive modeling for sales trends and feature impacts.


### Use Cases
1. **Exploratory Data Analysis:** Understand sales patterns, store performance, and external impacts.
2. **Predictive Modeling:** Build models for sales forecasting based on historical data and features.
3. **Business Insights:** Inform store management strategies to improve sales performance.


