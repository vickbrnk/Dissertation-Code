# Dissertation Code

CSV Files = Contains CSV Files\
C.1 = Objective Measures \
C.1.1 = Containment Index \
C.1.2 = Merge CI and Objective Measures \
C.2 = Mondays and Weeks \
C.2.1 = Matching Axios Waves to TimeSR Weeks \
C.3 = Converting Axios Files and Sentiment Calculation \
C.3.0 = Merge Age Sentiment with Final \
C.3.1 = HPS Sentiment Calculation \
C.3.2 = HPS Age Groups Sentiment Calculation \
C.3.3 = HPS Sentiment Calculation \
C.3.4 = Match HPS Sentiment and Final Survey File \
C.4 = Collection of Tweets \
C.4.1 = Raw Twitter Count and Plot \
C.4.2 = Merge and Count of Twitter \
C.4.3 = First Clean and Plot of Twitter \
C.4.4 = Pre-Processing No Source Tweets Twitter \
C.4.5 = Pre-Processing Source Tweets Twitter  \
C.5 = Collection of Reddit Submissions \
C.5.1 = Merge and Count of Reddit Submissions \
C.5.2 = First Clean and Plot Reddit Submissions \
C.5.3 = Pre-Processing Reddit Submissions  \
C.6 = Collection of Reddit Comments \
C.6.1 = Merge and Count of Reddit Comments\
C.6.2 = First Clean and Plot Reddit Comments \
C.6.3 = Pre-Processing Reddit Comments \
C.7 = Selection of Variables \
C.7.0 = Count after Pre-Processing \
C.7.1 =  Various Plots \
C.8 = VADER Sentiment Analysis \
C.8.1 = TextBlob Sentiment Analysis \
C.8.2 = BING Sentiment Analysis \
C.8.3 = AFINN Sentiment Analysis \
C.8.4 = NRC Sentiment Analysis \
C.8.50 = Weighting of VADER \
C.8.51 = Weighting of TextBlob \
C.8.52 = Weighting of BING \
C.8.53 = Weighting of AFINN \
C.8.54 = Weighting of NRC \
C.9.0 = Pearson Correlation test \
C.9.1 = Latent Profile Analysis \
C.9.11 = Latent Profile Analysis Details\
C.9.7 = Plot Range of SMD Sentiment Scores\
C.9.71 = Descriptive Stats SMD Sentiment Scores\
C.9.72 = Heatmap Plots\
C.9.73 = LPA Plots\




# Details of Code
**C.1 = Objective Measures** <em>(Code in R)</em>\
Contains cleaning of objective measures (Our World in Data), both the initial dataset and the final smoothed dataset used.

**C.1.1 = Containment Index** <em>(Code in R)</em>\
Contains prep of the Containment Index (Our World in Data).

**C.1.2 = Merge CI and Objective Measures** <em>(Code in R)</em>\
Contains prep and merge of the Containment Index and Objective measures (Our World in Data).

**C.2 = Mondays and Weeks** <em>(Code in R)</em>\
Contains code to create CSV file for looping when collecting Twitter and Reddit data.

**C.2.1 = Matching Axios Waves to TimeSR Weeks** <em>(Code in R)</em>\
Contains code matching the closest TimeSR week to Axios Interview Dates (Waves).

**C.3 = Converting Axios Files and Sentiment Calculation** <em>(Code in R)</em>\
First loops through all files and check missing values. Then converts all *.sav files to csv. Following this, answers to Q73 for Waves 33 to 36 are counted. Next, answers to Q107 and Q73 are counted for Waves 37 to 67. These are then merged together and the sentiment score is calculated with help of the equation.

**C.3.0 = Merge Age Sentiment with Final** <em>(Code in R)</em>\
Code to merge all sentiment scores in one file.

**C.3.1 = HPS Sentiment Calculation** <em>(Code in R)</em>\
Reads info from all excel files of HPS and calculates sentiment score with help of the equation.

**C.3.2 = HPS Age Groups Sentiment Calculation** <em>(Code in R)</em>\
Contains code calculating HPS sentiment for different age groups

**C.3.3 = Match HPS Sentiment and Final Survey File** <em>(Code in R)</em>\
Contains code matching the closest HPS week to examined week date and the final merge of all Survey Sentiments.


**C.3.4 = Match HPS Sentiment and Final Survey File** <em>(Code in R)</em>\
Contains code matching the closest HPS week to examined week date and the final merge of all Survey Sentiments.


**C.4 = Collection of Tweets** <em>(Code in R)</em>\
Contains code used to collect Tweets through Twitter Developer.

**C.4.1 = Raw Twitter Count and Plot.R** <em>(Code in R)</em>\
Contains code to count number of collected Tweets and plot these.

**C.4.2 = Merge and Count of Twitter** <em>(Code in R)</em>\
Contains code to count number of collected Tweets and merge them all into one collective file for cleaning.

**C.4.3 = First Clean and Plot of Twitter** <em>(Code in R)</em>\
Contains code to clean collected Tweets and plot.

**C.4.4 = Pre-Processing No Source Tweets Twitter** <em>(Code in R)</em>\
Contains code to pre-process Tweets without source-tweets and generate word clouds.

**C.4.5 = Pre-Processing Source Tweets Twitter** <em>(Code in R)</em>\
Contains code to pre-process Tweets with source-tweets and generate word clouds.

**C.5 = Collection of Reddit Submissions** <em>(Code in Python)</em>\
Contains code to collect Reddit Submissions on Google Colab.

**C.5.1 = Merge and Count of Reddit Submissions** <em>(Code in R)</em>\
Contains code to count number of collected Reddit submissions, merge the 4 queries into one per examined week and then merge all files into one collective file for cleaning.

**C.5.2 = First Clean and Plot Reddit Submissions** <em>(Code in R)</em>\
Contains code to clean Reddit submissions data and plot the count. Also, counts how many submissions had comments for the consideration of pulling the relevant comments.

**C.5.3 = Pre-Processing Reddit Submissions** <em>(Code in R)</em>\
Contains code to pre-process Reddit Submissions and generate word clouds.

**C.6 = Collection of Reddit Comments** <em>(Code in Python)</em>\
Contains code to collect Reddit Comments on Google Colab.

**C.6.1 = Merge and Count of Reddit Comments** <em>(Code in R)</em>\
Contains code to count number of collected Reddit comments, merge the 4 queries into one per examined week and then merge all files into one collective file for cleaning.

**C.6.2 = First Clean and PLot Reddit Comments** <em>(Code in R)</em>\
Contains code to clean Reddit comments data and plot the count. 

**C.6.3 = Pre-Processing Reddit Comments** <em>(Code in R)</em>\
Contains code to pre-process Reddit Comments and generate word clouds.

**C.7 = Selection of Variables** <em>(Code in R)</em>\
Contains code selecting final variables for all datasets. 

**C.7.0 = Count after Pre-Processing** <em>(Code in R)</em>\
Contains code counting volume of Reddit Comments, Submissions and Twitter posts.


**C.7.1 = Various Plots** <em>(Code in R)</em>\
Contains code plotting a variety of graphs in the final report.

**C.8 = VADER Sentiment Analysis** <em>(Code in Python)</em>\
Contains code applying VADER Sentiment Analysis to all columns in a given dataset on Google Colab.

**C.8.1 = TextBlob Sentiment Analysis** <em>(Code in Python)</em>\
Contains code applying TextBlob Sentiment Analysis to all columns in a given dataset on Google Colab.

**C.8.2 = BING Sentiment Analysis** <em>(Code in R)</em>\
Contains code applying BING Lexicon to all columns in a given dataset.

**C.8.3 = AFINN Sentiment Analysis** <em>(Code in R)</em>\
Contains code applying BING Lexicon to all columns in a given dataset.

**C.8.4 = NRC Sentiment Analysis** <em>(Code in R)</em>\
Contains code applying BING Lexicon to all columns in a given dataset.

**C.8.50 = Weighting of VADER** <em>(Code in R)</em>\
Contains code weighting the VADER sentiment scores for Tq, Tnq, and Rs.

**C.8.51 = Weighting of TextBlob** <em>(Code in R)</em>\
Contains code weighting the TextBlobs sentiment scores for Tq, Tnq, and Rs.

**C.8.52 = Weighting of BING** <em>(Code in R)</em>\
Contains code weighting the BING sentiment scores for Tq, Tnq, and Rs.

**C.8.53 = Weighting of AFINN** <em>(Code in R)</em>\
Contains code weighting the AFINN sentiment scores for Tq, Tnq, and Rs.

**C.8.54 = Weighting of NRC** <em>(Code in R)</em>\
Contains code weighting the NRC sentiment scores for Tq, Tnq, and Rs. Also plots the comments weights scores for various tables.

**C.9.0 = Pearson Correlation test** <em>(Code in R)</em>\
Contains code applying the Pearson Correlation test to all sentiment scores, surveys, and objective measures.

**C.9.1 = Latent Profile Analysis** <em>(Code in R)</em>\
Contains code performing LPA on different data sources, methods, and pre-processing decisions used.

**C.9.11 = Latent Profile Analysis Details** <em>(Code in R)</em>\
Contains code examining and pasting the grouping of variables in all LPA options.

**C.9.7 = Plot Range of SMD Sentiment Scores** <em>(Code in R)</em>\
Contains code plotting the range of the weighted and unweighted sentiment scores.

**C.9.71 = Descriptive Stats SMD Sentiment Scores** <em>(Code in R)</em>\
Contains code calculating descriptive statistics of SMD sentiment.

**C.9.72 = Heatmap Plots** <em>(Code in R)</em>\
Contains code cplotting SMD and Survey heatmaps for Pearson Coefficient.

**C.9.73 = LPA Plots** <em>(Code in R)</em>\
Contains code cplotting LPA groupings and pie charts.


