# WeRate-Twitter-Archive-Analysis
This is a project for Udacity's Data Analysis Nanodegree in which I wrangled, stored, and analyzed data from the WeRateDogs Twitter account.
## File Information
1. wrangle_act.html  
This is an html version of the Jupyter Notebook where I document my analysis process. 

2. twitter-archive-enhanced.csv  
This is an archive of basic tweet data about WeRateDog's tweets provided by Udacity. The data was extracted programmatically and required heavy cleaning on my part.

3. image_predictions.tsv  
Every image in the WeRateDogs Twitter archive was run through a neural network that classified the dogs into breeds. The resulting table contains the following columns:
     * the tweet ID
     * *p1*: The machine learning algorithm's first prediction for the dog breed
     * *p1_conf*: Percentage of confidence the algorithm has in its _p1_ prediction
     * *p2*: The algorithm's second prediction for the dog breed
     * *p2_conf*: Percentage of confidence the algorithm has in its _p2_ prediction
     etc...
4. tweet_json.txt  
I gathered each tweet's JSON data by querying Twitter's API using Python's Tweepy library and saved them in this txt file. 

5. twitter-archive-master.csv  
After gathering, assessing, and cleaning all the data from the previous three files, I saved them to this twitter-archive-master file to analyze it.

6. act_report.html  
This is an html version of a jupyter notebook where I report on my analysis findings and supplement my report with graphs.

7. wrangle_report.pdf  
This is a short report about my data wrangling efforts.

8. analysis_images folder  
This folder contains the graphs I created for my analysis.


