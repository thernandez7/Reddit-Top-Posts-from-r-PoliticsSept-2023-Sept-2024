# Title: Reddit-Top-Posts-from-r-PoliticsSept-2023-Sept-2024

### Creator
- **Author**: Tiziana Hernandez
- **Contact**: hernat@rpi.edu

### Subject
**Keywords**: Reddit, r/Politics, top posts, political discourse, politics, social media, Reddit API, 2023-2024

### Description
This dataset contains information about the top 500 posts from the subreddit r/Politics from September 18, 2023 - September 18, 2024. This data could be used to gain a comprehensive understanding of popular discourse, opinion trends, and information/misinformation dissemination within politics on Reddit. This data can be used for analyzing the political leanings of the posts, and identifying whether the top posts seem to exhibit left-leaning, right-leaning, or potentially misleading (fake news) tendencies.

**Each post object includes various metadata fields that provide detailed information about the post. Below are the relevant fields I used included in the Reddit API fetch:**
*id*: Unique identifier of the post.
*title*: The title of the post.
*score*: The score of the post (upvotes minus downvotes).
*url*: The URL of the post.
*selftext*: The text of the post (if it is a text post).
*author*: The username of the person who posted.
*created_utc*: The creation time of the post in UTC. (ONLY IN past_year_top_posts_API_RAW_DATA.json)
*num_comments*: The number of comments on the post.

**Added Field:** 
*created_date*: The creation time of the post in ISO 8601 format, converted from *created_utc*
*Rank*: The rank of the post ranging from 1-500 based on *score*

### Publisher
- "Student project, RPI"

### Contributors
- Tiziana Hernandez (Data Collector and Curator)

### Date
- **Creation Date**: 2024-09-17
- **Last Updated**: 2024-09-18

### Type
- **Type**: Dataset

### Format
- **Format**: application/json

### Identifier
- **Repository URL**: https://github.com/thernandez7/Reddit-Top-Posts-from-r-PoliticsSept-2023-Sept-2024

### Source
- Reddit API Documentation: https://www.reddit.com/dev/api

### Language
- **Language**: English

### Rights
- **License**: N/A 
- **Rights Holder**: Tiziana Hernandez 

### Coverage/Scope
- **Geographical Coverage**: Global
- **Temporal Coverage**: September 18, 2023 – September 18, 2024
