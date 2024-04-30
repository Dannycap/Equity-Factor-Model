# Equity-Factor-Model

In this code, we perform a comprehensive analysis of financial data, including the retrieval of financial information, calculation of various financial metrics, and visualization of the results. Additionally, we conduct a linear regression analysis to understand the relationships between factors from the Fama-French model and asset returns in the context of emerging markets. The code is structured into several key sections, each serving a specific analytical purpose.

Sections:

Data Preparation:

Fetch financial data from the Fama-French database, including Emerging Markets 6 Portfolios and Emerging 5 Factors. 

Data Analysis:

Calculate various financial metrics and statistics, such as cumulative returns, standard deviation, Sharpe ratio, drawdowns, covariance, correlation, beta values, and skewness. 

Data Visualization:

Create visualizations of the financial data, including line plots, ridgeline plots, heatmaps, and drawdown plots using 'matplotlib' and 'seaborn' libraries. Regression Analysis:

Perform linear regression analysis to understand the relationships between independent variables (Fama-French factors) and the dependent variable ('Emerging_SMALL_HiPRIOR'). Data Output:

Store calculated metrics and statistics in Pandas DataFrames. Print the summary of the regression analysis to assess variable relationships.

Data Storage:

Store analysis results and visualizations in DataFrames for further reference. Save some visualizations as image files with specific DPI settings. This code offers a holistic analysis of financial data, enabling the assessment of risk, returns, and relationships between factors and asset returns in emerging markets.


# Python Packages:

pandas (pd):

Website: https://pandas.pydata.org/
numpy (np):

Website: https://numpy.org/
matplotlib:

Website: https://matplotlib.org/
seaborn (sn):

Website: https://seaborn.pydata.org/
statsmodels.formula.api as smf:

Website: https://www.statsmodels.org/stable/formulas.html
statsmodels.api as sm:

Website: https://www.statsmodels.org/stable/index.html
joypy (joyplot):

Repository: https://github.com/sbebo/joypy
statsmodels.regression.rolling (RollingOLS):

Website: https://www.statsmodels.org/stable/regression.html

# Data
Ken French's Data Library:
Website: https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html
