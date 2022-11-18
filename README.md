# Youtube, the mirror of society?

Main notebook located on ```src/data-explore.ipynb```

## Abstract


Youtube has grown into a major source of information over the decade, with its main attributes being selectivity and anonymity. According to a study by [G.Stocking et al.(2020)](https://www.pewresearch.org/journalism/2020/09/28/many-americans-get-news-on-youtube-where-news-organizations-and-independent-producers-thrive-side-by-side/), a quarter of USA citizens consider Youtube as being an important news outlet. They are as likely to turn to independent channels as they are to established and well-known news organizations. Since the way to succeed on Youtube is strictly getting more views and traction on videos, an important amount of misinformation and bias is suspected from the creators. The content published might not be authentic and is prone to fakeness, aiming only to increase the number of views and fool the viewers into believing that something is true while it is probably as far from the truth as can be. 
Therefore, our goal is to “inspect” whether Youtube is a reliable and diverse source of information. By “reliable”, whether it focuses on certain types of events and whether it objectively transmits the events happening off-screen. By “diverse,” we mean whether it covers a large number of issues and provides different points of view or it reinforces a biased opinion on a specific topic. It seems to be an interesting lead since the platform users encounter a flood of information on a daily basis, and it often creates confusion in the public perception of the issue.  Additionally, it would be interesting to compare the evolution of the activity and topics on YouTube throughout the years with that of other popular social media platforms eventually. This could help us identify whether platforms are oriented towards specific topics or are all sharing the same information under different interfaces.


## Research questions: 

- Are Youtube videos mirroring the events happening off-screen in the real world? Do the activity of users, trends, and popular topics reflect the impactful and well-renowned phenomenons happening worldwide?
- Which type of events catch the public eye the most? Which topics gain the most views, interaction, and popularity on YouTube?
- Is controversy happening off-screen reflected through the likes and dislikes on YouTube videos covering them? Do controversial topics get more attention (more views and interaction)?
- Are the most discussed topics on Youtube also relevant on other social media/news outlets?
- What are the most popular types of topics covered by YouTube? Can YouTube be considered a news outlet, a platform for political views and interaction, a place to showcase your art, a platform to gain skills useful for your career...?


## Methods
First, we would like to proceed with a time series analysis to determine which topics were the most discussed during a specific time period. We would then compare these topics to an additional data set containing important events that occurred in the world during the same period. Thereby, we would be able to examine if Youtube puts enough emphasis on important subjects in real life. In order to quantify the amplitude of the event, we would like to quantify the number of people affected by the event. We would focus on events that have only occurred in English-speaking regions since the original data set only includes English YouTube channels. To determine which topic is discussed in each video, we would analyze the tags, the description, and the title of the video. 

Second, we would determine whether a topic is controversial or not by computing the dislike/like ratio. If this ratio is large, we will consider a video's topics and opinions as controversial. By doing that, we can classify videos according to how controversial they are. Then, we could compare the two datasets we have obtained and determine whether there is a correlation between the variables.

Then, we could further analyze the percentage of independent channels and news organization channels in the news/politics category, as well as the average views and subscribers they have, to observe how much people consider Youtube to be an important source of information. Also, we could compare the different narratives they are painting, by computing the percentage of videos with negative tones that they produce.

Finally, we would like to compare the issues brought up on Youtube to the ones on other social media platforms, such as Twitter and Instagram. In order to do that, we would compare the most relevant keywords on Youtube versus those on other platforms. 

## Additional datasets

- Google Trends for "trending topics" (per year, per category, per geo-location)
- Timeline of the 21st century: data from Wikipedia contains significant events in the course of time.
- Positive and Negative Word List.xlsx: data from Kaggle, a list of positive and negative words in order to study how some Youtube news outlets try to overstimulate their audience using negative words. 

## External libraries

- matplotlib
- seaborn
- sys
- os
- glob
- plotly

# Timeline:
- 18/11: Topic modeling, data clustering
- 25/11: Time series analysis, determine controversial topics, Filter news channels
- 02/12: Determine how to visually present our analysis
- 09/02: Finalize statistical analysis
- 16/12: Website and data story

# Organization:
- Lina: topic modeling, filtering out the topics of videos and regrouping them, writing of data story, time series analysis
- Simon: data clustering and website, time series analysis, compare our time series analysis with external datasets to assess "trends"
- Siyoung: Filter news channels (independent/mainstream media), time series analysis
- Arben: Determine controversial topics, time series analysis

# Questions:
- Are our research questions specific enough?




