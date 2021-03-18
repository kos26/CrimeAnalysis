# Exploring Schooling in Covid-19 Twitter Chatter Dataset
## Project for DSCI 521, Winter 2020

### Introduction and Background

Over a billion students worldwide are unable to go to school or university, due to measures to stop the spread of COVID-19. The pandemic is expected to have a huge impact on global education.

At their peak, the closures affected at least 55.1 million students in 124,000 U.S. public and private schools. Nearly every state either ordered or recommended that schools remain closed through the end of the 2019-20 school year.

Our proposed solutions is to use multiple models thats can predict and classify tweets that are supporting virtual/online school vs face-to-face school. This would give insights to school officials, government officials and the general public about making improvements while educating students.

Our proposed solution is to create multiple models that can predict and classify the type of crime. This can also help provide community insights on how to make improvements to reduce the crime from occuring in the first place. Another solution we intend to work on is predicting which neighborhoods are likely to increase and decrease in crime rates. 

Philadelphia Crime/Weather Data and Philadelphia Parking Violation:
From last term, these Philadelphia Crime/Weather Data were cleansed and integrated. We will integrate Philadelphia Parking Violation based on location features such as lat and lon. From this we will be able to create zip codes for crime predictive analysis. 

We'll be doing detailed analysis on text data and manually label each tweets after filtering out tweets which contains keywords. We'll apply the labeled dataset to machine learning models to predict and classify whether a tweet is supporting virtual education or face-to-face. The machine learning part of the project will be made up of three components: data transformation, data integration, and classification. For classification, we will do our best to implement all of the following model types: Logistic Regression, Decision Tree Classifier, Randomforest and Naive bayes.


# Table of Contents
1. [Team Members](#TEAM-MEMBERS)
1. [Datasets](#EXPLANATION-OF-DATASETS)
1. [Pre-Processing](#DATA-PRE-PROCESSING)
1. [Exploratory Data Analytics](#EXPLORATORY-DATA-ANALYTICS)
1. [Conclusion](#CONCLUSION)
1. [Final Presentation](#FINAL-PRESENTATION)


## TEAM MEMBERS

### Yiyun (Kate) Fan (yf366@drexel.edu)
- Background: 2nd-year PhD student from Drexel University’s School of Education
- Self-identified skills: Domain knowledge (education), Python programming, Network analysis, Project management
- Individual contributions: Conceptualization, Dataset Preparation, Collaboration on programming, Presentation.

### Shreekant Malviya (sm4546@drexel.edu)
- Background: 2nd- year MS in Information Systems minor in Applied Data Science
- Self-identified skills: Python programming, Data analysis & visualization, Project management
- Individual contributions: Data Analysis and modeling , Machine Learning, Data cleansing, Documentation and Presentation. 

### Kunal Sharma
- Background: 2nd-year MS in Data Science
- Self-identified skills: Programming, Project management, Data Analysis
- Individual contributions: Data engineering, Machine Learning, Data cleansing.


## EXPLANATION OF DATASETS
[Datasets]

## MAIN DATASETS
### A large-scale COVID-19 Twitter chatter dataset by Banda et al. (2020): 
- Uses Twitter Stream API to collect tweets since March 2020 based on the following keywords:<br> 
“COVD19”, “CoronavirusPandemic”, “COVID-19”, “2019nCoV”, “CoronaOutbreak”, “coronavirus”, “WuhanVirus”
- Has been sharing dehydrated daily dataset since March to the present day (as of 03/10/2021) on Github: 
https://github.com/thepanacealab/covid19_twitter
- Article introducing the dataset by the authors:<br>
Banda, J. M., Tekumalla, R., Wang, G., Yu, J., Liu, T., Ding, Y., & Chowell, G. (2020).<br>A large-scale COVID-19 Twitter chatter dataset for open scientific research--an international collaboration. arXiv preprint arXiv:2004.03688


## DATA-PRE-PROCESSING

[Data Acquisition and Per-Processing Report]
- Acquire Twitter API credentials
- Decide on the interested timeframe (May, Sept., Oct., Nov.)
- Build a hydrator to hydrate the COVID-19 Twitter dataset from the timeframe
- Filter the text of each tweets with keywords related to education: “teach”, “educat”, “school”, “student”, “university”, “college”
- Develop modules to allow user interactions:
<br>To download filtered dataset locally as their own structured database for further analysis.<br>
To input their own keywords and timeframe to filter the original covid-19 Twitter dataset.


## EXPLORATORY DATA ANALYTICS
[Exploratory Data Analytics]



## CONCLUSION
[Conclusion]
<br>The primary aim of this project was to classify educational tweets and determine whether the tweets will help us to identify reopening of educational institution during the covid19. By applying Feature engineering on text data to vectorize them using TDF-IDF vectorizer and suitable classifier models such as 'Naive-Bayes', 'Logistic regression' 'Decision-tree',and 'Random Forest' the project aimed to detect the mode of learning institutions are opting.<br><br>

Apart from Feature engineering and Classification, suitable Model evaluation and tuning like 'accuracy', 'recall', 'precision' and 'f1 score' metrics were calculated on `full_text` which can be seen in the table<br>
    
    
|                     | accuracy 	|   recall 	| precision 	|       f1 	|      auc 	|
|---------------------|-------------|-----------|---------------|-----------|-----------|
|     Naive_Bayes     | 0.808511 	| 0.863928 	| 0.911924  	| 0.887278 	| 0.614027 	|
| Logistic_Regression | 0.839866 	| 0.859734 	| 0.963415  	| 0.908626 	| 0.607514 	|
|    Random_forest    | 0.840985 	| 0.843318 	| 0.991870  	| 0.911582 	| 0.557225 	|
|    Decision_trees   | 0.802912 	| 0.855696 	| 0.915989  	| 0.884817 	| 0.590253 	|



## FINAL PRESENTATION
[Final Presentation]
(https://drexel.zoom.us/rec/share/17mfadn1t3GS0NTCx272qBPVjMlfyRPwomnVc4v7QAfPfvR5Ss8oN1z2cDtqfovc.opfOG53Tg24WuBNp  (Passcode: ?%6=mWVN))
