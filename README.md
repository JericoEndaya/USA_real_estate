# USA_real_estate

Time series analysis of the FOE stock price

Language: Python

Dataset: https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset?rvi=1, https://simplemaps.com/data/us-zips

Tools used: Jupyter Notebook

This project bloomed from a personal curiosity of mine, I wanted to see how prices evolved in the real estate industry of the USA. What I have found is that over time, price per square feet tend to increase over time which I have visualized with geographic heatmap that shows price per squarefeet per zip code. The dataset I have used has listings from the year 1901 to 2022, the majority of which originating from the east coast.

I have successfully predicted price per squarefeet using both random forests and xgboost with random forests outperforming the latter in my analysis.
MSE_XGB: 9782.376542406904, MSE_RF: 605.7690071242127

[USA_real_estate_notebook](https://nbviewer.org/github/JericoEndaya/USA_real_estate/blob/main/USA_real_estate.ipynb)
