# YouTube Landscape Analysis

## Project Overview
The **YouTube Landscape Analysis** project aims to provide comprehensive insights into the competitive landscape of YouTube channels. It focuses on analyzing competitor channels, audience engagement, and sentiment analysis to empower content creators and channel managers with valuable information for strategic decision-making.

Through meticulous examination of key metrics such as viewership trends, posting schedules, and audience interactions, this project offers tailored recommendations to optimize content strategy and enhance viewer engagement. By integrating quantitative analysis with qualitative methodologies like Natural Language Processing (NLP) and sentiment analysis, it delves deep into audience sentiments, preferences, and feedback, providing a holistic understanding of viewer behavior within the YouTube ecosystem.

With a primary emphasis on competitor analysis and the exploration of audience sentiments, the YouTube Landscape Analysis project equips stakeholders with actionable insights to navigate the dynamic YouTube landscape effectively.

## About Dataset
### Data extracted from youtube for competitor Analysis:
- **Number of columns:** 5 columns (channel_name, subscribers, views, total_videos, playlist_id)
- **Number of entries:** 4 YouTube channels

### Channel with highest number of video uploads:
- **Ken Jee’s channel**

### Data extracted from Ken Jee’s Channel for quantitative analysis:
- **Number of columns:** 7 columns (Title, Published_date, Views, Likes, Dislikes, Comments, videoid)
- **Feature Engineered columns:** 2 columns (Pub_Month, day)
- **Number of entries:** 287 entries

### Data extracted from Ken Jee’s Channel for sentiment analysis:
- **Number of columns:** 5 columns (author, date_updated, like_count, comment_text, public)
- **Number of entries:** 812 entries

## Collection Methodology
The collection methodology involved adhering to the guidelines provided by the Google Development Console and the YouTube Data API. Python functions were employed to facilitate the extraction process, ensuring compliance with data extraction protocols.

## Tools
The tools utilized for data extraction and analysis included the Google Development Console, the YouTube Data API, and Python programming language with relevant libraries and functions. These tools enabled efficient extraction and manipulation of data for comprehensive analysis.

## Analysis
### Top 10 videos with highest viewers:
- The video titled "How I would learn data science (If I have to start over)", posted on the 8th of May 2020, garnered the highest viewership among the observed dataset, with 1,399,761 viewers.

### Monthly posting trend:
- March consistently exhibits the highest number of videos posted, as evidenced by the visualization.

### Understanding Viewer Engagement: Analyzing Trends Over Time
#### Monthly viewers trend:
- May showcases the highest viewership, closely trailed by April, while October marks the lowest viewership. These insights are invaluable for decision-making processes.

#### Daily viewers trend:
- Friday consistently commands the highest viewership figures, followed closely by Monday. Conversely, Sunday consistently records the lowest viewership metrics.

### Correlation:
- The heatmap visualization indicates positive correlation among all numeric variables, except for Dislike, which lacks a significant correlation value.

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

# Analysis of the comments is still in progress
