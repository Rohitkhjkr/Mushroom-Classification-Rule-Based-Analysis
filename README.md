# Mushroom-Classification-Rule-Based-Analysis
Mushroom classification using exploratory data analysis, Chi-Square statistical testing, and Decision Tree rule extraction to identify edible and poisonous mushrooms.


# Project Overview
This project analyses the **Mushroom dataset** to investigate the characteristics associated with edible and poisonous mushrooms. The analysis combines **Exploratory Data Analysis (EDA)**, feature analysis, **Chi-Square statistical testing**, and a **Decision Tree classifier** to examine relationships between mushroom characteristics and their class. A key objective of the project is to transform the Decision Tree into an interpretable **rulebook**, providing human-readable classification rules for identifying mushrooms as either **Edible** or **Poisonous**.

# Objectives
The main objectives of this project are to:
- Load and structure the mushroom dataset using Python.
- Explore the distribution of edible and poisonous mushrooms.
- Analyse individual mushroom features and missing values.
- Examine relationships between features and the target class.
- Use Chi-Square tests to identify features associated with mushroom classification.
- Build a Decision Tree classifier.
- Extract interpretable classification rules from the Decision Tree.
- Create a rulebook showing rule conditions, outcomes, confidence, and support.

# Dataset
The project uses the **Agaricus-Lepiota mushroom dataset**.
The target variable is:
- `e` → **Edible**
- `p` → **Poisonous**
The dataset contains categorical characteristics describing different properties of mushrooms. The accompanying information file is also processed programmatically to extract attribute names and their possible values.

# Exploratory Data Analysis
Exploratory Data Analysis is performed to better understand the structure and characteristics of the dataset.
The analysis includes:
- Dataset dimensions
- Distribution of the target variable
- Number of edible mushrooms
- Number of poisonous mushrooms
- Number of unique values for each feature
- Missing-value counts
- Feature correlation with the encoded target class
