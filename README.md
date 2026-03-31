# North Carolina Campaign Finance Analysis 

This repository contains an exploratory data analysis (EDA) of North Carolina campaign finance records. Developed during the **Summer I 2024** semester for **IST 488: Data Sense Making**, this project investigates the statistical correlation between candidate expenditures, donor contributions, and final election outcomes.

## Project Overview

* **Goal:** To determine if higher campaign spending serves as a definitive predictor of electoral success in North Carolina.
* **Technologies & Libraries:** Python, Pandas (data manipulation), Matplotlib & Seaborn (visualization), and Jupyter/Google Colab.
* **Dataset:** Analyzes raw financial disclosure records including committee names, contribution amounts, and expenditure reports.

## Key Analytical Phases

### 1. Data Wrangling & Cleaning
The analysis involved ingesting multiple CSV datasets, handling missing values, and normalizing financial figures to ensure accurate cross-candidate comparisons.

### 2. Exploratory Data Analysis (EDA)
* **Correlation Mapping:** Utilized heatmaps to identify strong relationships between contribution aggregates and winning margins.
* **Trend Visualization:** Created scatter plots and regression lines to visualize how "Individual Donations in September" impacted late-stage campaign momentum.

### 3. Hypothesis Testing
The project includes a dedicated phase for hypothesis development, testing the significance of donation timing versus total volume in predicting voter behavior.

## Repository Structure

* `Final_Notebook.ipynb`: The complete, polished analytical pipeline containing all code, visualizations, and final conclusions.
* `Hypothesis_Assignment.ipynb`: Detailed statistical testing and variable analysis.
* `Outline_Notebook.ipynb` & `Draft_Notebook.ipynb`: Early-stage data exploration and project milestones.
* `Data_Sensemaking_Reflection.ipynb`: A technical post-mortem on the methodologies used and insights gained.

## How to Run

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/aunnani03/nc-campaign-analysis.git](https://github.com/aunnani03/nc-campaign-analysis.git)
    ```
2.  **Open in Environment:** Upload the `.ipynb` files to **Google Colab** or open them locally using **Jupyter Notebook**.
3.  **Install Dependencies:**
    ```python
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns
    ```

## Credits
* **Author:** Andrew Nnani
* **Course:** IST 488: Data Sense Making (Summer I 2024)
* **Institution:** University of North Carolina at Greensboro
