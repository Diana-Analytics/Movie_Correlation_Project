# Movies Correlation Project Overview
## Objective:

The aim of this project is to analyze the correlation between movie budgets and their gross revenue, using data cleaning, preprocessing, and visualizations to uncover patterns.

   ### Data Cleaning:
  Dealt with missing values by:
   -   Using mode imputation for all categorical (object) columns.
   -   Using median imputation for all numeric columns.
   -   Implemented for loops to handle imputation across all relevant columns.
   -   Standardized all column headers using title() to ensure consistency across the dataset.

   ### Data Preprocessing:
  -  Converted all object (categorical) columns to categorical data types using .astype('category').
  -  Applied one-hot encoding via .cat.codes to convert categorical columns into numeric values, making the dataset suitable for analysis.
  ### Exploratory Data Analysis:
  Scatter Plot:
  -  Created a scatter plot to visualize the relationship between the Budget and Gross revenue.
  This provided an initial overview, showing that movies with higher budgets tend to generate higher gross revenue.
  
  Regression Plot:
-  Used Seaborn’s regplot to further investigate the relationship between Budget and Gross.
  The plot displayed a regression line, clearly indicating a positive relationship between movie budgets and gross revenue.

 Correlation Analysis:
 -    Converted the categorical data and used a heatmap to visualize the correlation between all features, especially focusing on Budget and Gross.
   The heatmap showed a strong positive correlation between the Budget and Gross, confirming the trend observed in the scatter plot and regression analysis.

  ### Data Preprocessing Techniques: 
  Data cleaning, imputation, and encoding were crucial in preparing the data for analysis.
  
  ### Visualization: 
  Scatter plots, regression plots, and heatmaps helped visualize and solidify the relationship between key variables.

### Technologies Used:
-  pandas for data manipulation and cleaning.
-  Seaborn and Matplotlib for visualizations.
-  NumPy for numerical operations.

  ### Conclusion:
-   The analysis concludes that there is a high correlation between movie budgets and the gross revenue generated.This suggests that movies with larger budgets tend to make more money at the box office.
### Key Insights:

  **Budget matters**: 
  The data suggests a strong relationship between a movie's budget and its potential revenue.
  
