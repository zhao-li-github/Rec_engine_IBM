# Recommendations with IBM Project  

### Summary:  
In this project, I aim to build a few recommendation engines to recommend articles to the users in the IBM Watson Studio platform. 

### Content:
1. "Data" folder:  
- "user-item-interactions.py": the CSV file that contains the detailed information of articles (title, description, and body text).  
- "articles_community.csv": the CSV file that contains the detailed information of articles (title, description, and body text).  
  
2. "Recommendations_with_IBM_ver2.ipynb":  
- Part I. Exploratory Data Analysis: explore the data and clean the duplicates.  
- Part II. Rank Based Recommendations: first find the most popular articles based on how many times they have been viewed by all users in the platform, then recommend the most popular articles to a user. This is a good rec algorithm for new users when we have no idea what kind of topics he/she will be interested in.  
- Part III. User-User Based Collaborative Filtering: first find the "neighbors" of a user based on similar articles they've viewed, then recommend unseen articles to a user that his/her neighbors have viewed.  
- Part IV. Content Based Recommendations: first use NLP techniques to find similarities between articles using their titles, and then recommend unseen articles to a user based on the articles he/she have viewed.  
- Part V. Matrix Factorization: build a recommenadtion engine using machine learning technique. The matrix factorization technique used is SVD (Singular Value Decomposition). Using the model, I can predict how likely a user will view an article. I also find that the accuracy to estimate the train set increases when the number of latent features increases, while the accuracy to estimate the test set decreases when the number of latent features increases, this gives us an idea to find a balance between overfitting and underfitting. 

### Acknowledgement:
This project is a part of the Udacity Data Scientist Nanodegree Program. The data was provided by IBM Watson Studio platform.
