Titanic Dataset - Exploratory Data Analysis (EDA)
This repository contains an exploratory data analysis (EDA) project on the Titanic dataset using Python, Pandas, Seaborn, and Matplotlib.

Objective
Perform visual and statistical exploration of the Titanic dataset to extract insights about the passengers and factors affecting their survival.

Files
EDA titanic.ipynb: Jupyter Notebook containing the full EDA process.

Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

 EDA Overview
1. Dataset Overview
- Dataset loaded from Seaborn’s built-in Titanic dataset.
- Basic info, shape, missing values, and statistical summary using `.info()`, `.describe()`, and `.isnull().sum()`.

2. Univariate Analysis
- Visualized categorical variables using countplots.
- Plotted histograms for continuous variables: `age`, `fare`, `sibsp`, and `parch`.

3. Bivariate Analysis
- Analyzed relationships between `survived` and other features using countplots and boxplots.
- Observed gender, class, fare, and age influences on survival.

4. Correlation & Pairplots
- Generated heatmap of correlations between numerical features.
- Pairplot to explore patterns by survival status.

  Key Insights
- Females and passengers in higher classes had higher survival rates.
- Younger passengers were more likely to survive.
- Passengers who paid higher fares generally had better survival chances.
- Being with family improved survival chances.


Feel free to fork, star, and contribute! ⭐

