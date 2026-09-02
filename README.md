🥭 Mango Market Data Analysis

An exploratory data analysis of mango market data from 2017 to 2020, investigating price differences across years and the profitability of organic and conventional mangoes.

The project combines data cleaning, exploratory analysis, statistical testing and visualization using Python.

🎯 Objectives

The analysis focuses on two main questions:

1. Were mango prices higher in 2019 or 2020?
2. Are organic or conventional mangoes more profitable?

📊 Analysis

The project follows a complete data analysis workflow:

* Import and combine data from CSV and JSON sources
* Inspect the dataset and identify duplicate observations
* Detect and remove price outliers using the Interquartile Range (IQR) method
* Compare mango prices between 2019 and 2020
* Calculate both simple and volume-weighted average prices
* Analyze price differences across regions
* Compare profitability between organic and conventional mangoes
* Explore relationships between price, volume and profitability
* Validate observed differences using statistical hypothesis testing
* Visualize distributions and comparisons using Matplotlib and Seaborn

🔍 Key Findings

Mango Prices

The analysis found that mango prices were higher in 2019 than in 2020 across the different comparisons performed.

A statistical test was also used to evaluate whether the difference in average prices between the two years was statistically significant.

Organic vs. Conventional

Organic mangoes showed higher profitability per unit than conventional mangoes in the analyzed dataset.

This relationship was also examined across different regions and validated using statistical testing.

🛠️ Technologies

* Python
* Pandas — data manipulation and analysis
* NumPy — numerical operations
* Matplotlib — data visualization
* Seaborn — statistical visualization
* SciPy — statistical hypothesis testing
* Jupyter Notebook

🚀 Running the Analysis

Clone the repository:

git clone https://github.com/YOUR-USERNAME/mango-market-data-analysis.git

Install the required dependencies:

pip install pandas numpy matplotlib seaborn scipy

Then open ProfitableMangoesAnalysis.ipynb using Jupyter Notebook, JupyterLab or Google Colab.

📚 Context

This project was developed as part of a Big Data & Business Analytics course and focuses on applying Python-based data analysis techniques to a practical business dataset.
