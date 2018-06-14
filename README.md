Overview:

I'm doing analysis of tweets in 2016 of the three Debates, it's too late for me now to get those tweets so I need to find a way to extract those tweets as Twitter provides a limit to extract tweets through Twitter API older than 7-9 days from the current date of extraction. Below are some of the useful links and process I followed to get old tweets.

I've collected the twitter IDs of the users who tweeted about each of the debate from the dataset provided by Harvard Business School from https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PDI7IN.

Each Debate file has around 3M twitter IDs.

I've used Hydrator(downloaded from https://github.com/DocNow/hydrator which's used to retrieve tweets specific to that ID) and gave the datasets first-debate, second-debate, third-debate that I downloaded earlier to retrieve tweets. As there are Data Rates applied on Twitter on Hydrator as it does on several other APIs, it takes time to import the data. I imported some percentage of tweets from random twitter IDs.

You can go through this https://gwu-libraries.github.io/sfm-ui/posts/2017-09-14-twitter-data website to know various sources from where you can get the twitter data.

You can also use the code provided here https://github.com/Jefferson-Henrique/GetOldTweets-python to extract the tweets older than 7-9 days from the current date.

Presidential_Debate_USA_Analysis: This notebook file mentions various sources online which are useful to extract trending twitter data such as presidential election debate USA 2016, election data of various countries etc., It has the step by step procedure to get the twitter data, basic data eploration, cleaning text, analysing the sentiment of the tweet using textblob in general and also specific to each candidate.

Twitter_Authentication_code: This notebook file has the code to access and extract tweets just in case if you want to do so rather than using hydrator and then can use the 'Presidential_Debate_USA_Analysis' notebook file for further analysis after you get the required data.

Note: You cannot share the tweets data but you can share twitter IDs, so i'm not displaying any output for the analysis.

Please do let me know for any changes.

Thanks
