# Python-Capstone-project---Social-Media-Engagement-Analysis
**Introduction** 
	Social media platforms generate massive amounts of interaction data from users across different countries. This data includes engagement metrics such as likes, comments, shares, post types, and content categories. These interactions often vary depending on user demographics such as age, as well as how frequently users share or repost content and the sentiment associated with it.
Social media engagement refers to the interactions users have with content, including likes, comments, and shares, which indicate how audiences respond to posts. Understanding this data is essential for improving content strategies and maximizing audience engagement.
This project primarily focuses on using Python to analyse the data, identify patterns and trends, and understand the factors that influence user interaction.

**Problem Statement**
	Despite the availability of large datasets, Python enables efficient handling and analysis of data. Raw and unstructured data can be converted into meaningful insights by applying pre-processing techniques such as data cleaning, handling missing values through imputation, and data visualization.

**ontent Performance**
1. Post Types with Highest Engagement
Analysis shows that visual content (videos and images) generates the highest engagement. Posts with higher visual appeal and vividness attract more likes, comments, and shares. 
Insight:
Video-based and image-based posts outperform text-based posts due to better user attention and interaction.
2. Best-Performing Content Category
Certain content categories consistently achieve higher engagement due to their relevance and emotional appeal.
 Insight:
•	Entertainment and informative content tend to perform better 
•	Content aligned with audience interests increases interaction
3.  Countries with Highest Engagement Rate
Engagement varies across countries due to differences in:
•	Digital behaviour 
•	Cultural preferences 
•	Social media usage patterns 
Insight:
Some regions show significantly higher average engagement, indicating strong audience activity and content resonance.

**User Trends**
1.  Impact of Age on Engagement
User engagement differs across age groups:
•	Younger users are generally more active and responsive 
•	Older users show relatively lower interaction rates 
Insight:
Age is a key factor influencing engagement behaviour and content preference.
2.  Verified vs Non-Verified Accounts
Verified accounts typically receive:
•	Higher visibility 
•	Greater trust from users 
Insight
      Verified users tend to have higher engagement due to credibility and reach advantages.

**Behavioural Insights**
1.  Best Time of Day for Impressions
Engagement is influenced by posting time, as users are more active during certain hours.
Research shows that timing and day of posting significantly affect engagement levels. 
Insight:
 	Posts published during peak activity hours receive more impressions and interactions.
2. Device Type Impact on Watch Time
User behaviour differs across devices:
•	Mobile users consume more short-form content 
•	Desktop users may engage more deeply with long-form content 
Insight:
 	Device type affects watch time and engagement patterns.

**Sentiment Analysis**
1. Best Performing Sentiment
Content with positive or emotionally engaging sentiment tends to perform better.
Insight:
•	Positive content attracts more likes and shares 
•	Emotional content increases interaction 
2.  Behaviour of Negative/Neutral Sentiment Posts
•	Negative sentiment may generate discussions (comments) 
•	Neutral content typically results in lower engagement 
Insight:
Different sentiment types influence different engagement metrics:
•	Likes & shares → driven by positive content 
•	Comments → often driven by controversial or negative content. 
Research also shows that likes and shares are stronger engagement indicators compared to comments, which represent deeper but less frequent interaction. 

**PROJECT CODE EXPLANATION**
**Data Exploration**
1.	Read() – Read the csv format data from the file
2.	Info(), describe() dtype() – It is used to understand the datatype, missing values and statistical distribution of the data
3.	Isnull(), duplicates(), drop(), - It is used to find the null value in the column, to identify the duplicates of the data and to remove the duplicates in the data.
4.	Shape – To identify the shape of the data
5.	Size – To identify the total number of column in the data
6.	Fillna() – To fill the missing value in the data
7.	Value_counts() – To check the repeated values.
8.	Unique(), nunique() – Show the unique value in the data

