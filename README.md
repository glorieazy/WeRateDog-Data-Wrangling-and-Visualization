## WeRateDog Data Analysis
This project encompases detailedly all the branches involved in analysing a Dataset ranging from Data Collection, Data Wrangling and Exploratory Data Analysis. 

### Dataset
3 Major Datasets are collected and used in this analysis. The first dataset is a comma separated file twitter-archive-enhanced.csv(comma separated file) provided by the project supervisor. The second file was downloaded programmatically from a URL provided using the request library as image_prediction.tsv (Tab Separated File). The third file was gotten from user's tweet on Twitter by querying Twitter API using my provided Authentication details.
### Summary of Findings
After the datasets are being properly accessed using the necessary methods(visual and programmatical), the issues derived are cleaned and merged where necessary and stored as **Twitter Master Dataset** for further exploration. Below are the findings generated:
1. Total Tweet length Average is 96.8
2.  The most common breed is **GOLDEN RETRIEVER**
3.  The least common breeds are **Scotch_terrier, standard_schnauzer, groenendael, silky_terrier, Scottish_deerhound, Bouvier_des_Flandres, Lumber, Irish_wolfhound, Japanese_spaniel.**
4.  **CHARLIE and LUCY** is the most common dog name
5.  **TWITTER for iPhone** is the most common tweet source
6.  The User tweets mostly on **Mondays**
7.  Retweet_count and Favorite_count has a high strong positive correlation (0.81)