# California House Prediction

### **Created by: FikriAditya**

---

## Overview
This project focuses on predicting house prices in California, set against the backdrop of the 1990 housing market scenario. With property prices reaching high levels during this period, this analysis offers insights into real estate investment strategies, aiding in identifying profitable opportunities.

---

## Contents

1. **Business Problem Understanding**
2. **Data Understanding**
3. **Exploratory Data Analysis**
4. **Data Preparation**
5. **Modeling**
6. **Conclusion and Recommendation**
7. **Deployment**

---

![California Housing](https://www.puredestinations.co.uk/wp-content/uploads/2019/09/top-things-to-do-in-San-Francisco-header--1600x500.jpg)

## Business Understanding

**Context:**
In 1990, California experienced a significant surge in property prices, influenced by factors like a strong economy, rapid population growth, and limited land availability. This project aims to understand these dynamics and provide a data-driven approach to pricing properties effectively.

**Challenge:**
The challenge lies in accurately predicting house prices in various Californian locales, considering multiple factors that influence these prices, such as location, property type, and economic conditions.

---

## Data Understanding

*(This project utilizes a comprehensive dataset that represents the housing market in California as of 1990. The dataset, sourced from the California Census data, includes a wide range of features such as median house values, median income, housing median age, total rooms, total bedrooms, population, households, and proximity to the ocean. Each record in the dataset corresponds to a district and includes aggregated data about the households within that district. The richness of this dataset allows for an in-depth analysis of housing prices, taking into account various socio-economic and geographic factors that might influence these prices. Understanding these nuances is crucial for developing accurate predictive models and making informed decisions in the real estate market)*

---

## Exploratory Data Analysis

*(The Exploratory Data Analysis (EDA) phase of this project focused on uncovering patterns, anomalies, and relationships within the California housing dataset. Initial steps involved a thorough examination of data distributions, where we observed the range and common values for crucial features like median house values, median income, and age of houses. Histograms and scatter plots were extensively used to visualize these aspects, revealing, for instance, a skewed distribution in house values, suggesting a concentration of more affordable houses compared to high-value properties.

Correlation analysis was another critical component, where we examined how different variables relate to the median house value. Notably, median income emerged as a strong predictor, indicating a direct correlation with housing prices. Geospatial analysis was also conducted to understand regional variations in housing prices, highlighting areas with exceptionally high or low prices. This analysis was complemented by heatmaps to visualize high-density clusters.

The EDA also involved identifying outliers and handling missing data, ensuring the integrity and reliability of the subsequent modeling process. Through these explorations, we gained valuable insights into the factors that drive house prices in California, setting a strong foundation for building our predictive models.)*

---

## Data Preparation

*(In the data preparation stage, we performed several key steps to ensure the dataset was primed for effective modeling. This involved cleaning the data by addressing missing values, where we opted for imputation strategies based on the nature of each feature. We also conducted feature engineering to enhance the dataset's predictive power, creating new variables that better represented the underlying real estate dynamics. To address potential skewness in the data, we applied normalization techniques, ensuring that all features contributed equally to the model. Finally, the dataset was split into training and test sets, providing a robust framework for both training our models and evaluating their performance objectively.)*

---

## Modeling

*(In the modeling stage of our project, we selected LightGBM (Light Gradient Boosting Machine) as our final model due to its efficiency and high performance for large datasets. LightGBM is known for its fast training speed and lower memory usage, which made it particularly suitable for our comprehensive California housing dataset. This algorithm excels in handling categorical features and complex data structures, which was crucial given the diverse range of variables in our dataset, such as median income, age of houses, and geographic location.

We fine-tuned the LightGBM model's hyperparameters to optimize its performance, using a combination of grid and random search techniques for the best results. The model demonstrated excellent predictive accuracy in our validation tests, with a significant reduction in both bias and variance compared to initial baseline models. Its ability to efficiently process large amounts of data and accurately predict housing prices made it an ideal choice for our analysis.)*

---

## Conclusion and Recommendation

*(Bencmark model use a LightGBM for a model prediction house California
The model achieves an R2 value of approximately 0.73, indicating that it explains about 73% of the variance in house prices.
The average MAPE is around 17.66%, suggesting predictions deviate by an average of 17.66% from actual prices..)*


1. Improve Data Quality: Focus on ensuring that training and testing data are representative and current, which is crucial for the accuracy and reliability of the model.
2. Iterative Model Enhancement: Allocate time for regular maintenance and enhancements to the model. This will help in maintaining its accuracy over time.
3. Feature Engineering: Deepen the feature engineering process to better address outliers and market segmentation.
4. Ensemble Modeling: Consider using ensemble models to further improve the accuracy and reliability of the predictions.
5. Continuous Testing: Regularly test the model with up-to-date market data to ensure it remains relevant and accurate in changing market conditions.

Implementing these recommendations will enable real estate businesses to refine their price predictions, reduce investment risks, and make more informed, data-driven decisions.

---

## Deployment


*For more details, please refer to the [[California House Prediction.ipynb](https://github.com/Fikria12/Machine-Learning/blob/main/California_House_Prediction.ipynb)https://github.com/Fikria12/Machine-Learning/blob/main/California_House_Prediction.ipynb)](https://github.com/Fikria12/Streamlit-California)https://github.com/Fikria12/Streamlit-California Jupyter notebook.*
