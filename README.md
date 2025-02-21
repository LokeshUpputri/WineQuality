# WineQuality
AAI-500 – Team Project
Group 1:
- Lokesh Upputri
- Safwan Syed

# Wine Quality Prediction Project

## Overview

This project aims to analyze and predict the quality of wines based on various physicochemical properties. The dataset consists of two separate CSV files for red and white wines, as well as a combined dataset that merges both. The analysis will focus on understanding the relationships between the wine characteristics and their quality ratings, which can be useful for winemakers and consumers alike.

## Dataset Description

### 1. Wine Quality Red Dataset (`winequality-red.csv`)

- fixed acidity: The amount of fixed acids in the wine (g/dm³).
- volatile acidity: The amount of volatile acids in the wine (g/dm³).
- citric acid: The amount of citric acid in the wine (g/dm³).
- residual sugar: The amount of residual sugar in the wine (g/dm³).
- chlorides: The amount of chlorides in the wine (g/dm³).
- free sulfur dioxide: The amount of free sulfur dioxide in the wine (mg/dm³).
- total sulfur dioxide: The amount of total sulfur dioxide in the wine (mg/dm³).
- density: The density of the wine (g/cm³).
- pH: The pH level of the wine.
- sulphates: The amount of sulphates in the wine (g/dm³).
- alcohol: The alcohol content of the wine (%).
- quality: The quality rating of the wine (scale from 0 to 10).


### 2. Wine Quality White Dataset (`winequality-white.csv`)
This dataset contains information about white wines, with the same features as the red wine dataset.


### 3. Combined Wine Quality Dataset (`combined_winequality.csv`)

This dataset merges both the red and white wine datasets into a single file, allowing for a comprehensive analysis of wine quality across both types.


## Data Format

The datasets are in CSV format, with semicolon (`;`) as the delimiter. The first row contains the headers, and subsequent rows contain the data entries.

### Example of Data Entry

```csv
fixed acidity;volatile acidity;citric acid;residual sugar;chlorides;free sulfur dioxide;total sulfur dioxide;density;pH;sulphates;alcohol;quality
7.4;0.7;0.0;1.9;0.076;11.0;34.0;0.9978;3.51;0.56;9.4;5
```

## Project Goals

- Data Exploration: Analyze the datasets to understand the distribution of features and their relationships with wine quality.
- Data Preprocessing: Clean and preprocess the data for analysis, including handling missing values and normalizing features.
- Model Development: Develop predictive models to estimate wine quality based on the physicochemical properties.
- Model Evaluation: Evaluate the performance of the models using appropriate metrics (e.g., accuracy, precision, recall).
- Visualization: Create visualizations to illustrate the findings and relationships in the data.


## Tools and Libraries

- **Python**: The primary programming language for data analysis and modeling.

- **Pandas**: For data manipulation and analysis.

- **NumPy**: For numerical operations.

- **Matplotlib/Seaborn**: For data visualization.

- **Scikit-learn**: For machine learning and model evaluation.


## Getting Started

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/wine-quality-prediction.git
   cd wine-quality-prediction
   ```


2. **Install Required Libraries**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Run the Analysis**:

- Open the Jupyter Notebook or Python script provided in the repository to start the analysis.


## Acknowledgments

- The datasets used in this project are publicly available and can be found on the UCI Machine Learning Repository.

- Special thanks to the contributors and the community for their support and resources.


