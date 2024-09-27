## Python - Jupyter-Notebook - Predicting Real Estate Prices In Amsterdam


**GitHub does not allow loading the dataset, it is only a preview.**

**It is recommended to run the file in Google Colab by pressing the button at the top of the page in the preview.**
Alternatively, follow [THIS LINK](https://colab.research.google.com/github/Vojinovic-M/python-predicting-real-estate-prices-amsterdam/blob/main/Amsterdam.ipynb) to Google Colab.

The dataset I used is available on Keggle and the link to it can be found in the file attached.

**A project done for my Artificial Intelligence class using Python on Google Colab.**

**My goal was to predict real estate prices in Amsterdam based on a dataset from 2021 using machine learning models. To do this, I went through several stages:**

**1. Collecting Data: I imported all the necessary libraries, including NumPy, Seaborn, Pandas, and others. I uploaded the dataset file in the CSV format and checked its validity.**

**2. Data Analysis: I read the file and elaborately show its contents, visualizing them through tables and graphs and presenting a statistical analysis of the data, highlighting the ranges of values in each column.**

**3. Data Preprocessing: I remove incomplete values, format column and remove unnecessary ones. After this I present more visualization in the form of heatmaps and histograms as to better understand the dataset. Finally, I split the data for training and testing (ultimately testing in 4 different scenarios with splits as following: 90-10, 80-20, 60-40, 50-50). Scalers are also imported and defined here.**

**4. Model Selection: For this project, I chose Linear Regression, Random Forest Regression, and Cross-Validation using GridSearchCV. I found these to be the most applicable to the nature of the data.**

**5. Training, Testing and Interpretation: All models showed high performance, with random forest regressor and cross-validation standing out for their ability to generalize new data (both scoring ~0.96 during training and ~0.93 during testing). They were considerably more accurate than the linear regression model, which saw ~0.77 in the training phase and ~0.89 in the testing phase.**
 
**Future work may include exploring additional complex models or further optimizations to improve accuracy or model speed. Still, the results I got are promising and indicate the potential for successful application of machine learning models in this context.**
