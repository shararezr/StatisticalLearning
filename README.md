# Statistical Analysis of Life Expectancy Dataset (WHO)

![R](https://img.shields.io/badge/language-R-brightgreen.svg)
![IDE](https://img.shields.io/badge/IDE-RStudio-blue.svg)

## Overview

This project aims to analyze the *Life Expectancy* dataset provided by the World Health Organization (WHO) to explore various factors affecting life expectancy across different countries. Through statistical analysis, we seek to answer questions about the relationships between life expectancy and factors such as healthcare expenditure, mortality rates, lifestyle habits, and education. 

### Dataset

The dataset used in this project contains data from various countries and includes key factors such as:
- Life expectancy
- Healthcare expenditure
- Infant and adult mortality rates
- Immunization coverage
- Lifestyle and health-related factors (e.g., alcohol consumption, smoking)
- Education and schooling levels
- Country income classification (developed vs. developing)

The primary goal is to uncover significant insights from the data to guide policy decisions and better understand the factors influencing life expectancy.

## Key Questions

The project will focus on answering the following questions:

### 1. **Impact of Predicting Factors on Life Expectancy**
   - Do the initial predicting factors chosen truly affect life expectancy?

### 2. **Key Predictors of Life Expectancy**
   - What are the main variables that most significantly influence life expectancy?

### 3. **Healthcare Expenditure**
   - Should countries with lower life expectancy values (<65) increase their healthcare expenditure to improve average lifespan?

### 4. **Mortality Rates**
   - How do infant and adult mortality rates affect life expectancy?

### 5. **Lifestyle and Behavior**
   - Is there a positive or negative correlation between life expectancy and factors like eating habits, lifestyle, exercise, smoking, and alcohol consumption?

### 6. **Impact of Education**
   - What is the impact of schooling on human lifespan?

### 7. **Alcohol Consumption and Life Expectancy**
   - Does life expectancy have a positive or negative relationship with alcohol consumption?

### 8. **Population Density**
   - Do densely populated countries tend to have lower life expectancy?

### 9. **Immunization Coverage**
   - What impact does immunization coverage have on life expectancy?

### 10. **Developed vs. Developing Countries**
   - Does the dataset provide enough evidence to suggest that developed countries have a higher average life expectancy compared to developing countries?

### 11. **Human Development and Life Expectancy**
   - Do countries that allocate a higher proportion of resources to human development tend to have higher life expectancy?

### 12. **Most Frequent Range of Life Expectancy**
   - What is the most frequent range of life expectancy in the dataset?

## Methodology

The analysis involves the following steps:

1. **Data Exploration & Preprocessing**: 
   - Cleaning and transforming the data to ensure it is in a usable format.
   - Checking for missing values and handling them appropriately.

2. **Statistical Analysis**: 
   - Performing various statistical tests to examine correlations, patterns, and relationships between life expectancy and other variables.
   - Using regression analysis, correlation analysis, and other statistical methods to draw conclusions.

3. **Data Visualization**: 
   - Visualizing data trends and relationships using graphs such as scatter plots, histograms, and heatmaps.
   - Plotting correlation matrices and relationships between key factors affecting life expectancy.

4. **Modeling**: 
   - Developing models to predict life expectancy based on various predictors.

## Data Analysis Tools

- **R Programming Language**: For data analysis and statistical modeling.
- **RStudio IDE**: For writing and executing R code.
- **Libraries**: 
   - `dplyr`, `ggplot2`, `tidyr`, `caret` for data manipulation, visualization, and modeling.
   - `lm()` for linear regression analysis.
   - `cor()` for correlation analysis.

## Results & Insights

By the end of this project, we aim to uncover valuable insights about the factors influencing life expectancy globally, identify the key predictors of life expectancy, and provide policy recommendations based on our findings.

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/life-expectancy-analysis.git
   cd life-expectancy-analysis
