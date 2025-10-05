# Movie-Industry-Correlation-Analysis-in-Python

Welcome to my exploratory data analysis project focused on uncovering correlations between key features in the movie industry. Using a Kaggle dataset of global films, I cleaned, transformed, and visualized the data to understand how variables like budget, gross earnings, runtime, and ratings interact.

📁 Project Overview
This project walks through:
- Cleaning and preprocessing a real-world movie dataset
- Handling missing values with strategic imputation and filtering
- Visualizing relationships between features using scatter plots and regression lines
- Computing and interpreting correlation matrices (numeric and encoded categorical)
- Highlighting which features most strongly influence gross earnings

🧰 Tools & Libraries Used
- Python 3.9+
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib & Seaborn for visualizations

📊 Key Insights
- Budget vs Gross Earnings: Strong positive correlation (~0.71), indicating higher budgets tend to yield higher returns.
- Votes and Score: Moderate correlation with gross, suggesting audience engagement and quality matter.
- Genre and Rating: Show negative correlations with gross, hinting at genre-specific performance trends.
- Categorical Encoding: Converted object types to category codes to include them in correlation analysis.

🧼 Data Cleaning Highlights
- Dropped rows with critical missing values (runtime, company, released, etc.)
- Imputed budget and gross with mean values; rating with mode
- Extracted clean release year from messy date strings
- Converted object columns to categorical codes for full correlation matrix

📈 Visuals Included
- Scatter plot: Budget vs Gross
- Regression plot: Budget vs Gross (Seaborn)
- Heatmaps: Correlation matrices for numeric and encoded features

📂 Dataset Source
Kaggle: The Movie Industry Dataset

🚀 How to Run
- Clone the repo
git clone https://github.com/your-username/movie-correlation-analysis.git
- Install dependencies
pip install pandas numpy matplotlib seaborn
- Run the notebook
Open Correlation in Python.ipynb in Jupyter or Colab

🙋‍♀️ About Me
I'm Sofia Crasto, a Data Analyst and Product Logic Specialist based in Abu Dhabi. I specialize in strategic data wrangling, stakeholder-ready storytelling, and building hybrid dashboards that blend technical depth with business clarity.  
