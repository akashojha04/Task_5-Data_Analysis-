# Titanic Survival Analysis: EDA & Predictive Strategy

## Project Objective
The goal of this project was to conduct a comprehensive **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover the socio-economic and demographic drivers of survival. This analysis serves as a data-backed foundation for building high-accuracy predictive models.

* **Robust Imputation:** Addressed missing values by filling *Age* with the median and **Embarked** with the mode to maintain the dataset's statistical distribution.
* **Spatial Feature Engineering:** Extracted **Cabin Decks** from raw strings to analyze how a passenger's physical location on the ship impacted their survival odds.
* **Dimensionality Awareness:** Categorized "Unknown" cabins, revealing a high correlation between missing location data and lower-class status.
* **Outlier Detection:** Isolated significant outliers in **Fare** distributions to understand the impact of extreme wealth on rescue priority.

## Analytical Framework & Tools
* **Data Manipulation:** `Python`, `Pandas`, `Seaborn`, `Matplotlib`
* **Visualization Suite:** `Matplotlib` and `Seaborn` for trend identification and statistical plotting.
* **Core Methodology:** Applied correlation matrices and bivariate analysis to determine the relationship between variables like *Pclass*, *Fare*, and *Survival*.

## Key Business & Predictive Insights
The analysis yielded several critical insights into the "Women and Children First" protocol and socio-economic biases:

1.  **Socio-Economic Influence:** Confirmed that **Passenger Class (Pclass)** and **Fare** are the strongest predictors of survival, reflecting a clear "wealth-first" rescue priority.
2.  **Gender-Based Survival:** Statistical evidence shows **Gender** was a primary deciding factor, with females seeing significantly higher survival rates across all classes.
3.  **Spatial Access:** Passengers located on higher decks (**B, C, D**) had superior access to lifeboats compared to those in lower-class sections.
4.  **Demographic Concentration:** Identified that the majority of the risk-exposed population (3rd Class) consisted of males aged between 20–40.

## Repository Structure
| File | Description |
| `titanic_analysis.ipynb` | Jupyter Notebook containing the full Python code and visualizations. |
| `train.csv / test.csv` | The raw Titanic datasets. |
| `README.md` | Project documentation and executive summary. |
