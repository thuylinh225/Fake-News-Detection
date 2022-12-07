# Fake-News-Detection

Fake news is the deliberate spread of misinformation via traditional news media or via social media. False information spreads extraordinarily fast. This is demonstrated by the fact that, when one fake news site is taken down, another will promptly take its place. In addition, fake news can become indistinguishable from accurate reporting since it spreads so fast. People can download articles from sites, share the information, re-share from others and by the end of the day the false information has gone so far from its original site that it becomes indistinguishable from real news (Rubin, Chen, & Conroy, 2016).

Thus, detecting false information or fake news can help people get the true stories, good information. In this project, I use data from Kaggle, were downloaded from the link: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

There are two data from this resource, included true and fake data. There are 23481 entries in fake and 21417 entries in true data. There are 4 columns in each data, included: title, text, subject and date. After reading these two data, I will create a new data by concatenating them together for training model later.

In this project, there are 5 parts:

(1) Gather data, determine the method of data collection and provenance of the data.  
(2) Identify Unsupervised Learning Problem.  
(3) EDA - Inspect, Visualize, and Clean the data.   
(4) Building and training models:   

+ NMF 
+ Kmeans 
+ Random Forest 
+ Logistic Regression 
+ Decision Tree 

(5) Summary 
