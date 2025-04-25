# Elevate-Labs---Task-2-Exploratory-Data-Analysis-EDA-
# Task 2: Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective
The goal of this task was to perform Exploratory Data Analysis (EDA) on a dataset using statistics and visualizations to understand the data, identify trends, detect anomalies, and derive basic insights.

## Dataset
The dataset used is the [Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv), which includes information about passengers aboard the RMS Titanic such as:
- Name, Age, Gender
- Ticket fare
- Passenger class (Pclass)
- Survival status (Survived)

## Tools & Libraries Used
- *Python*
- *Pandas* for data manipulation
- *Matplotlib* & *Seaborn* for visualizations
- *Plotly* for interactive charts
- *Jupyter Notebook* for analysis

## Key Steps in the EDA Process

1. *Data Loading*: Loaded the Titanic dataset from a public URL.
2. *Summary Statistics*:
   - Used describe() to generate mean, median, std, etc.
   - Checked data types and missing values using info() and isnull().
3. *Data Visualization*:
   - Created *histograms* and *boxplots* to explore distributions and detect outliers.
   - Plotted a *correlation matrix* to study relationships between numerical features.
   - Used *pairplot* to visualize interactions between key variables.
4. *Patterns & Trends*:
   - Analyzed survival rate by gender, passenger class, and age.
   - Detected key patterns such as higher survival for females and 1st-class passengers.
5. *Interactive Plot*:
   - Created an interactive scatter plot (Age vs. Fare) using Plotly to explore individual-level patterns.

## Insights
- Female passengers had a higher survival rate.
- 1st-class passengers were more likely to survive.
- Age and Fare showed some correlation with survival.

## Screenshots

![image](https://github.com/user-attachments/assets/7ad3e5eb-477b-4385-9edb-f1b2f0c9f4d8)
![image](https://github.com/user-attachments/assets/12efb5a0-d709-4ee8-86b7-b998e8cfb4cc)
![image](https://github.com/user-attachments/assets/776faec9-7509-4f01-8b12-c961cce673e9)
![image](https://github.com/user-attachments/assets/85d225bc-10bd-4774-8965-d55f458afee7)

## How to Run
1. Clone the repository
2. Open titanic_eda.ipynb in Jupyter Notebook or Google Colab
3. Run all cells

