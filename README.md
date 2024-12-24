# Depressed Dataset Analysis

This project analyzes a dataset containing demographic, lifestyle, and health information of individuals to explore the relationships between factors such as income, mental health, physical activity, and more. The primary focus is to understand the connection between depression and other variables in the dataset.

## Dataset Overview

The dataset contains the following columns:

- **Name**: Full name of the individual.
- **Age**: Age of the individual.
- **Marital Status**: Marital status (e.g., Married, Single, Widowed, Divorced).
- **Education Level**: Highest level of education completed.
- **Number of Children**: Total number of children.
- **Smoking Status**: Whether the individual is a smoker or not.
- **Physical Activity Level**: Self-reported physical activity level (e.g., Active, Sedentary, Moderate).
- **Employment Status**: Employment status (e.g., Employed, Unemployed).
- **Income**: Annual income in USD.
- **Alcohol Consumption**: Frequency of alcohol consumption (e.g., Low, High, Moderate).
- **Dietary Habits**: Self-reported diet habits (e.g., Healthy, Unhealthy, Moderate).
- **Sleep Patterns**: Self-reported sleep patterns (e.g., Good, Poor, Fair).
- **History of Mental Illness**: Whether the individual has a history of mental illness (Yes/No).
- **History of Substance Abuse**: Whether the individual has a history of substance abuse (Yes/No).
- **Family History of Depression**: Whether the individual has a family history of depression (Yes/No).
- **Chronic Medical Conditions**: Whether the individual has any chronic medical conditions (Yes/No).

## Analysis and Visualizations

The project performs various analyses to understand how depression relates to different factors. Several visualizations were created using Python, highlighting key insights from the dataset. Below are the visualizations included in the project:

### 1. **Income vs Depression Histogram**

The histogram shows the relationship between **income** and the **count** of individuals with a history of depression. It highlights income distribution among individuals who are reported to have depression.

![Income vs Depression Histogram](images/histplot.jpg)

- **X-Axis**: Income levels (in USD).
- **Y-Axis**: Count of individuals in each income range.
- **Key Insight**: This plot helps in visualizing how income is distributed across individuals with a history of depression.

### 2. **Correlation Matrix**

The correlation matrix provides insights into the relationships between all columns in the dataset. It helps identify any significant correlations between variables like income, age, and history of mental illness.

![Correlation Matrix](images/correlation.jpg)

- **Color Scale**: The colors indicate the strength and direction of correlations. Darker colors indicate stronger correlations.
- **Key Insight**: The matrix is useful to identify strong correlations, like between **mental illness** history and other factors such as **income**, **employment status**, and **physical activity**.

### 3. **Income vs Age Scatter Plot**

This scatter plot shows the relationship between **income** and **age**. It provides a visual understanding of how income is distributed by age, especially among individuals with depression.

![Income vs Age Scatter Plot](images/scatterplot.jpg)

- **X-Axis**: Age of the individual.
- **Y-Axis**: Annual income in USD.
- **Key Insight**: This plot illustrates the relationship between age and income, providing insights into how individuals' income varies with age and the potential relationship with depression.
