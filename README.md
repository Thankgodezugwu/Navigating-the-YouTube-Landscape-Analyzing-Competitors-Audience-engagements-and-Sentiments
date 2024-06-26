# YouTube Landscape Analysis 

## Project Overview
The **YouTube Landscape Analysis** project aims to provide comprehensive insights into the competitive landscape of YouTube channels. It focuses on analyzing competitor channels, audience engagement, and sentiment analysis to empower content creators and channel managers with valuable information for strategic decision-making.

Through meticulous examination of key metrics such as viewership trends, posting schedules, and audience interactions, this project offers tailored recommendations to optimize content strategy and enhance viewer engagement. By integrating quantitative analysis with qualitative methodologies like Natural Language Processing (NLP) and sentiment analysis, it delves deep into audience sentiments, preferences, and feedback, providing a holistic understanding of viewer behavior within the YouTube ecosystem.

With a primary emphasis on competitor analysis and the exploration of audience sentiments, the YouTube Landscape Analysis project equips stakeholders with actionable insights to navigate the dynamic YouTube landscape effectively.

## About Dataset
### Data extracted from youtube for competitor Analysis:
- **Number of columns:** 5 columns (channel_name, subscribers, views, total_videos, playlist_id)
- **Number of entries:** 4 YouTube channels

![pc1](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/9186f688-de81-4eb1-b86b-1a5146b6fb82)


### Channel with highest number of video uploads:
- **Ken Jee’s channel**

![pc2](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/3bb09298-f6c8-40ee-bb85-dbbd51638243)

### Data extracted from Ken Jee’s Channel for quantitative analysis:
- **Number of columns:** 7 columns (Title, Published_date, Views, Likes, Dislikes, Comments, videoid)
- **Feature Engineered columns:** 2 columns (Pub_Month, day)
- **Number of entries:** 287 entries

![pc3](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/9e2dc762-fcf4-4d49-a225-7d7d24b314da)


### Data extracted from Ken Jee’s Channel for sentiment analysis:
- **Number of columns:** 5 columns (author, date_updated, like_count, comment_text, public)
- **Number of entries:** 812 entries

![pc4](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/c4874bc7-d61a-4030-9215-9f97eb2af3ed)


## Collection Methodology
The process of gathering data adhered meticulously to the guidelines established by the YouTube Data API. To execute this, a sophisticated approach utilizing Python programming was employed. Within this framework, a suite of custom functions was developed specifically tailored to extract the requisite data. These functions were meticulously crafted to ensure compliance with the stringent data extraction protocols mandated by the platforms. By leveraging Python's versatility and the capabilities of these custom functions, the extraction process was not only efficient but also robust, guaranteeing the integrity and accuracy of the collected data.

## Tools
The tools utilized for data extraction and analysis included the Google Development Console, the YouTube Data API, and Python programming language with relevant libraries and functions. These tools enabled efficient extraction and manipulation of data for comprehensive analysis.

## Analysis
### Top 10 videos with highest viewers:
- The video titled "How I would learn data science (If I have to start over)", posted on the 8th of May 2020, garnered the highest viewership among the observed dataset, with 1,399,761 viewers.

![pc5](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/4023763d-93d3-4321-9fab-5f27cd30ad5b)


### Monthly posting trend:
- March consistently exhibits the highest number of videos posted, as evidenced by the visualization.

![pc6](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/2df28e37-7a3c-4deb-b9ab-1b06dfab3274)


### Understanding Viewer Engagement: Analyzing Trends Over Time
#### Monthly viewers trend:
- May showcases the highest viewership, closely trailed by April, while October marks the lowest viewership. These insights are invaluable for decision-making processes.

![pc7](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/b5412ad2-26c9-4e97-a125-5418b36879bd)


#### Daily viewers trend:
- Friday consistently commands the highest viewership figures, followed closely by Monday. Conversely, Sunday consistently records the lowest viewership metrics.

![pc8](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/1595803b-0481-4e30-a213-b4e491f1d9e0)


### Correlation:
- The heatmap visualization indicates positive correlation among all numeric variables, except for Dislike, which lacks a significant correlation value.

![pc9](https://github.com/Thankgodezugwu/Navigating-the-YouTube-Landscape-Analyzing-Competitors-Audience-engagements-and-Sentiments/assets/145191825/7d1b2520-8370-44b6-a3ba-394c0953f1a1)


## Recommendation
Based on the analysis conducted, the following recommendations are proposed to enhance YouTube channel performance and decision-making:
1. **Content Strategy Optimization:**
   - Given the success of the video "How I would learn data science (If I have to start over)", consider producing more content similar to this, as it resonates well with the audience and attracts high viewership.
2. **Strategic Posting Schedule:**
   - Since March consistently sees the highest number of videos posted, continue to prioritize this month for content release. Additionally, consider adjusting posting schedules to capitalize on peak viewership days like Fridays and Mondays.
3. **Engagement Enhancement:**
   - Focus on strategies to boost engagement on Sundays, which consistently records the lowest viewership. This could involve promoting special content or engaging with the audience through interactive features like live streams or Q&A sessions.
4. **Further Analysis of Dislikes:**
   - Investigate the factors contributing to the lack of significant correlation with Dislike metrics. Understanding audience sentiments and preferences regarding disliked content can provide valuable insights for content refinement and audience satisfaction.

Implementing these recommendations can lead to a more informed content strategy and improved viewer engagement, ultimately driving channel growth and success.

# Analysis of the comments sentiments is still in progress
