# Stellar Classification and Analysis Using VizieR Catalog

## Introduction

This project involves the detailed analysis and visualization of stellar properties using a dataset obtained from the VizieR Catalog. The dataset contains various parameters of stars, including temperature, luminosity, radius, absolute magnitude, star type, star color, and spectral class. The primary goal is to understand the relationships between these parameters, perform comparative analyses, and develop predictive models using machine learning techniques.

## Objective

The objectives of this project are as follows:

1. To perform exploratory data analysis (EDA) to understand the distribution and relationships between various stellar parameters.
2. To build predictive models for classifying stars based on their properties.
3. To apply clustering algorithms to identify distinct groups of stars.
4. To analyze how star color and spectral class correlate with other properties like temperature, luminosity, and radius.
5. To develop regression models to predict the absolute magnitude of stars from other features.
6. To create an interactive data exploration tool for visualizing and analyzing the dataset.

## Data Acquisition and Preprocessing

The dataset was sourced from the VizieR Catalog, containing the following columns: Temperature (K), Luminosity (L/Lo), Radius (R/Ro), Absolute magnitude (Mv), Star type, Star color, and Spectral Class. Data preprocessing steps included handling missing values, normalizing or scaling the data, and encoding categorical variables.

## Exploratory Data Analysis (EDA)

1. **Descriptive Statistics**: Calculated mean, median, standard deviation, and other statistical measures for the parameters to summarize the data.
2. **Correlation Analysis**: Generated a correlation matrix to identify relationships between the variables, visualized using a heatmap to highlight the strength and direction of correlations.
3. **Visualizations**: Created scatter plots, histograms, and pair plots to explore relationships and distributions among temperature, luminosity, radius, and absolute magnitude. For instance, pair plots helped visualize pairwise relationships and distributions of these variables.

## Analysis and Visualization

1. **Stellar Classification**:
   - **Temperature-Radius Relation**: Plotted a scatter plot to explore the relationship between temperature and radius, with color coding for star types.
   - **Comparative Analysis by Star Type**: Created box plots to compare distributions of temperature, luminosity, radius, and absolute magnitude across different star types.
   - **Spectral Class vs. Absolute Magnitude**: Visualized the relationship between spectral class and absolute magnitude using scatter plots.

2. **Density Plots**:
   - Generated density plots for temperature, luminosity, and radius to visualize their distributions and identify any underlying patterns or clusters.

3. **Outlier Detection**:
   - Used box plots to detect and analyze outliers in temperature, luminosity, and radius.

4. **Color and Spectral Class Distribution**:
   - Created bar charts to visualize the distribution of star colors and spectral classes, providing insights into the composition of stars based on these attributes.

5. **Hertzsprung-Russell Diagram**:
   - Plotted an HR Diagram to display the relationship between temperature and absolute magnitude, inverting the y-axis to show brighter stars at the top.

## Predictive Modeling

1. **Star Type Prediction**:
   - Implemented machine learning models such as decision trees, random forests, and support vector machines to classify stars based on their properties. Evaluated model performance using accuracy, precision, recall, and F1-score.

2. **Clustering**:
   - Applied clustering algorithms like K-means and hierarchical clustering to group stars based on their similarities in temperature, luminosity, and radius. Visualized the clusters using 2D or 3D plots.

3. **Regression Analysis**:
   - Built regression models to predict the absolute magnitude of stars from temperature, luminosity, and radius. Evaluated model performance using metrics like mean squared error (MSE) and R-squared value.

## Interactive Data Exploration Tool

Developed an interactive dashboard or web application using tools like Plotly Dash or Streamlit, allowing users to explore the dataset visually. Features included filtering by star type or color, dynamic plotting of data points, and statistical summaries of the properties.

## Summary

This project provided a comprehensive analysis of stellar properties, leveraging various data visualization and machine learning techniques. By exploring the relationships between different stellar parameters, developing predictive models, and creating interactive tools, the project aimed to enhance our understanding of stellar classification and characteristics. The insights gained from this analysis can be valuable for further astronomical research and education.
