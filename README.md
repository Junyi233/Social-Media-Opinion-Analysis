### Project Title:

**Analyzing User Opinions on "SPY X FAMILY" Second Season Using Social Media Data**

### Project Overview:

In this project, social media analysis was conducted on the popular animated series "SPY X FAMILY" using Python skills. The analysis aimed to collect and analyze user feedback expressed on various social media platforms, including Twitter, Facebook, Instagram, WeChat, TikTok, and others. The primary objective was to gain insights into the discussions and sentiments surrounding the release of the second season of "SPY X FAMILY."

### Project Steps:

**Keyword Selection:** The keyword "SPY X FAMILY" was selected as the point of interest, directly relating to the animated series under analysis.

**Data Collection:** A substantial dataset of tweets mentioning "SPY X FAMILY" was collected using Python scripts to access the Twitter API. The goal was to gather approximately 10,000 tweets to ensure a representative sample.

**Preliminary Data Analysis:** After collecting the data, preliminary data analysis was conducted to clean and prepare the dataset for further analysis. This step included the removal of duplicates, handling missing values, and structuring the data for analysis.

**Word Cloud Generation:** Word clouds were created for data visualization to gain an initial understanding of the most common topics and keywords associated with "SPY X FAMILY." Word clouds visually represented the frequency of words in the collected tweets.

**Sentiment Analysis:** Sentiment analysis was performed on the collected tweets to evaluate the overall sentiment (positive, negative, neutral) of user opinions regarding the second season of "SPY X FAMILY." Python's natural language processing (NLP) libraries and machine learning techniques were used for sentiment classification.

**Insights and Conclusions:** In the final phase of the project, insights were summarized and described based on the analyses conducted. The sentiment analysis results were interpreted, common themes or concerns expressed by users were identified, and actionable insights were provided.

### Project Deliverables:

- A Python script for data collection from social media platforms, with a focus on Twitter.
- A clean and structured dataset of 10,000 tweets mentioning "SPY X FAMILY."
- Word cloud visualizations illustrating the most frequently mentioned words.
- Sentiment analysis results, including the proportion of positive, negative, and neutral tweets.
- A project report summarizing the insights gained and the sentiment of user feedback regarding the second season of "SPY X FAMILY."

This social media analysis aimed to provide valuable insights for fans and creators of the animated series, as well as for anyone interested in understanding the public reception of "SPY X FAMILY" season two. The project serves as an example of how data analysis can extract meaningful information from the vast world of social media discussions.


### Insights:

1. **A specific hashtag is chosen by individuals** despite the fact that other ones already have the same meaning and with very minimal differences. The differences can be capitalization versus no capitalization or using an underscore instead of a dot. In the example of the 10 most popular hashtags, #SPY_FAMILY has more than 1,400 counts whereas #SPYFAMILY or #SPYxFAMILY each has less than 200. **Consideration can be given to understand the psychological factors** behind users’ decisions in choosing a hashtag and come up with film names that create the best **publicity effects**.

2. **The timing of events is crucial**. Spy Family had already gained a good reputation from the first season, and therefore, **excitement surrounded the second season**. Furthermore, media also contributed to increasing viewer anticipation. As a result, there were already a significant number of tweets even before the release date. The number of tweets increased significantly and peaked on the release date as viewers were eager to discuss the show after watching it. Some users even extracted cute video clips from the episode, which also generated high views.

3. **Influential tweets are not necessarily authored by the most influential individuals**. **A hypothesis can be formulated that the more people retweet a tweet, the more visibility the tweet will gain**. There might be a correlation between the number of followers/following of an account and the impact of that account’s tweet, but more substantial factors influence tweet popularity. This is a valuable finding, especially for organizations seeking to promote a product. Some may opt for influencers with many followers, but the influence of the authors is not the sole determinant. Companies may need to consider not only the number of followers or following of the accounts but also other significant factors, such as the content of the tweets. In fact, the most influential tweets are those with quality photos.

4. Although the TextBlob package for Python is a valuable tool for Natural Language Processing, it is not without limitations. **It should be noted that TextBlob cannot interpret emojis**, which can alter the meaning of the tweets or convey the authors' emotions. Furthermore, TextBlob analyzes words, phrases, and exclamations to assess polarity and subjectivity. However, real-life human language is complex and can surpass the computer's interpretation abilities. This is demonstrated through the example of the three most negative tweets, which are, in fact, positive tweets that employ negative keywords for emphasis.

In conclusion, this project is a practical application of text analytics to real-world scenarios. **Valuable findings have been generated through data analysis** when sufficient data is available. **Leveraging these methods and techniques for larger datasets in other projects may be considered**. For instance, **analyzing public sentiment towards a presidential election using data collected via social media** platforms like Facebook, Instagram, Discord, and Twitter. It would be intriguing to assess the polarity and subjectivity scores of citizens' comments and compare the analysis results to actual outcomes. These analytical techniques can serve as powerful tools for explaining or even predicting real-world events as long as **the necessary and sufficient data is obtained**.
