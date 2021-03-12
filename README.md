# Recommendations with IBM Project

### Summary:
In this project, I aim to apply the data engineering skills learned in the Udacity Data Science Nanoprogram to analyze the tweets and text messages sent during disasters and build a supervised model to classify a message into various categories. The purpose to build such model is to help disaster response organizations to filter and pull out the most important/relevant messages to them. Two pipelines are built in this project: an ETL pipeline and an ML pipeline. Then, a web app provided by the course (and revised by me) will extract data to provide data visualization, and use the trained model to classify new messages.  

### Summary:  
In this project, I aim to build a few recommendation engines to recommend articles to the users in the IBM Watson Studio platform. 

### Content:
1. "Data" folder:  
- "user-item-interactions.py": the CSV file that contains the detailed information of articles (title, description, and body text)  
- "articles_community.csv": the CSV file that contains the detailed information of articles (title, description, and body text)  
  
2. "Recommendations_with_IBM_ver2.ipynb": the notebook for the project. 
- "Starbucks_ML.ipynb": the notebook for the second half of the project. Here I loaded the SQL database for the two types of offers, and trained random forest classifier model to identify whether a customer is a good "target" for each offer type, based on their demographic features. 
- "Merged_bogo_df" and "Merged_discount_df": the two SQL databases created by "Starbucks ETL.ipynb" that contains the merged and cleaned data for BOGO offers and discount offers, respectively. 
- "visuals.py": this is the Python codes to plot the predictive features with their normalized weights in the model. This was from "Udacity Machine Learning Nanoprogram" that I took last year.

### Acknowledgement:
This project is a part of the Udacity Data Scientist Nanodegree Program. The data was provided by IBM Watson Studio platform.
