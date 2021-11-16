The repository is laid out as follows:

**Analysis on content & user database**
-- SQL (folder)
----Query 1 (file)
  Query to identify Top 5 most popular pieces of content consumed this week. 

----Query 2 (file)
  Query to identify Number of weekly active users for the latest full week (Monday – Sunday). 
  WAU is calculated by counting registered users with > 60 seconds dwell time between Monday-Sunday.

----Query 3 (file)
  Query to identify	Top 5 pieces of content from each content type consumed this week by only active users 

**Product & User data Analysis**

-- Part 2 ML (folder)
----Scripts/Notebooks (files)
  1 jupyter notebook detailing the data processing, exploration, analysis and ML modelling
  
----Models (folder)
  There are 6 models pickled in the folder with 3 each for two datasets. The dataset datamA is the one provided originally excluding the marital status & state data.
  The dataset datamb is the derived from dataset datamA by removing the column providing information on the number of news subscriptions

----Data (folder)
  Scores.csv containing the final scores for the prediction using the model 'Random Forest_datamA.sav'
  User insights.ppt containing the findings & insights for the business stakeholders

