# [Youtube, mirror of society?](https://siyounglee00.github.io/Project-Website/)

Notebook organization contained in the ```./src/README.md```

## Abstract


Youtube has grown into a major source of information over the decade, with its main attributes being selectivity and anonymity. According to a study by [G.Stocking et al.(2020)](https://www.pewresearch.org/journalism/2020/09/28/many-americans-get-news-on-youtube-where-news-organizations-and-independent-producers-thrive-side-by-side/), a quarter of USA citizens consider Youtube as being an important news outlet. They are as likely to turn to independent channels as they are to established and well-known news organizations. Since the way to succeed on Youtube is strictly getting more views and traction on videos, an important amount of misinformation and bias is suspected from the creators. The content published might not be authentic and is prone to fakeness, aiming only to increase the number of views and fool the viewers into believing that something is true while it is probably as far from the truth as can be. 
Therefore, our goal is to “inspect” whether Youtube is a reliable and diverse source of information. By “reliable”, whether it focuses on certain types of events and whether it objectively transmits the events happening off-screen. By “diverse,” we mean whether it covers a large number of issues and provides different points of view or it reinforces a biased opinion on a specific topic. It seems to be an interesting lead since the platform users encounter a flood of information on a daily basis, and it often creates confusion in the public perception of the issue.  Additionally, it would be interesting to compare the evolution of the activity and topics on YouTube throughout the years with that of other popular social media platforms eventually. This could help us identify whether platforms are oriented towards specific topics or are all sharing the same information under different interfaces.


## Research questions: 

- Are Youtube videos mirroring the events happening off-screen in the real world? Do the activity of users, trends, and popular topics reflect the impactful and well-renowned phenomenons happening worldwide?
- Which type of events catch the public eye the most? Which topics gain the most views, interaction, and popularity on YouTube?
- Are the most discussed topics on Youtube also relevant on other social media/news outlets?
- What are the most popular types of topics covered by YouTube? Can YouTube be considered a news outlet, a platform for political views and interaction, a place to showcase your art, a platform to gain skills useful for your career...?
- Are Youtube news channels relevant news sources?


## Methods
In order to analyze the most discussed topics in channels classified as "News and Politics" during a certain time period, we will conduct a time series analysis. Our focus will be on specific events that occurred between 2005 and 2019, which we have divided into five categories: sports, technology, politics, health, and trending topics on YouTube. For each category, we have selected a few representative events to study, such as the football World Cup, tennis, basketball, the Olympic games, and baseball in the sports category. Our methodology involves identifying specific keywords related to each event and then aggregating the number of views and number of videos uploaded per month. This will allow us to compare the coverage of different events over time and observe any differences in exposure between cyclical events (e.g. the football World Cup, which occurs every four years). 

In addition to the timeseries analysis, we will first perform an N-gram analysis to extract meaningful insights from this data. Indeed, we will be dealing with a large amount of textual data. Therefore, this will help us identify frequently occurring words and word pairings, which can allow us to identify trends in the data. After conducting the N-gram analysis, we will also apply Latent Dirichlet Allocation (LDA), a statistical generative algorithm that groups words and assigns prevalence and saliency to specific words based on their probability distribution. This will help us gain a better understanding of the underlying themes and patterns in the data.

## Additional datasets

Dataset organization can be found in the ```/datasets/README.md```.

## External libraries

The list of the external libraries used can be found in ```environment.yml```.

# Timeline:
- 18/11: Topic modeling, data clustering
- 25/11: Time series analysis, determine controversial topics, Filter news channels
- 02/12: Determine how to visually present our analysis
- 09/02: Finalize statistical analysis
- 16/12: Website and data story

# Organization:
- Lina: topic modeling, filtering out the topics of videos and regrouping them, writing of data story, time series analysis
- Simon: LDA, wordclouds + N-grams, Website formatting
- Siyoung: Filter news channels, time series analysis, Discussion
- Arben: Timeseries analysis, extract events from wiki article




