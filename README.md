# Mall Customer Segmentation

Mall customer segmentation involves analyzing customer behavior in purchasing products. The goal is to identify the patterns to which different customers belong.

# Requirements
Python 3.8+ Jupyter Notebook - Kaggle Notebook is preferrable.

# Dataset
Mall Customer Segmentation : https://www.kaggle.com/datasets/hunter0007/ecommerce-dataset-for-predictive-marketing-2023

# How to Run The Notebook.
1. Login to Kaggle.com
2. Visit https://www.kaggle.com/datasets/hunter0007/ecommerce-dataset-for-predictive-marketing-2023  link
3. Click on "New Notebook" Option Available on the top of the screen.
4. Download the ".ipynb" File attached in the current repository, select the right version
5. Upload On the New Notebook place by clicking on Import Notebook option.
6. Run The Notebook program

# Run the program in virtual envrionment python
1. Create virtual environment
2. Activate virtual environment
3. Install requirements.txt
4. Run jupyter notebook and Open the .ipynb notebook file on the localhost:8888

# Key Data Insights
* From doing EDA (exploratory data analysis) we can see the percentage count of customer who reordered.
* From doing EDA, we can see that most of the ordering of product takes place in afternoon and in the morning and the most preferable day to order is Sunday.
* By applying Apriori Algorithm Association rule we can see the connection between department.
* we calculated the support ,confidence and lift for the transaction and seeing the lift score we can say that the people prefer  pasta sauce on dry pasta.
* Then we scaled the data and apply Principal Component Analysis on it to see variance of features
# Model Performance
The KMeans algorithm is applied to the model. The optimal number of clusters for fitting is 18.

# Ethics Report
We have to scale and perform PCA for the model to give better results.
