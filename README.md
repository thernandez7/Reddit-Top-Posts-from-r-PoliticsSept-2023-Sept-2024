## Title: Reddit-Top-Posts-from-r-Politics-Sept-2023-Sept-2024

### Creator
- **Author**: Tiziana Hernandez
- **Contact**: hernat@rpi.edu

### Subject
**Keywords**: Reddit, r/Politics, top posts, political discourse, politics, social media, Reddit API, 2023-2024

### Description
This dataset contains information about the top 500 posts from the subreddit r/Politics from September 29, 2023 - September 29, 2024. This data could be used to gain a comprehensive understanding of popular discourse, opinion trends, and information/misinformation dissemination within politics on Reddit. This data can be used for analyzing the political leanings of the posts, and identifying whether the top posts seem to exhibit left-leaning, right-leaning, or potentially misleading (fake news) tendencies.

### Data Collection Method
Reddit API using PRAW
Posts are aggregated by month and year

**Number of Top-posts per month:** 
Saved 1 posts for 2023-09   in reddit_top_posts_by_month/2023-09.json
Saved 21 posts for 2023-10  in reddit_top_posts_by_month/2023-10.json
Saved 17 posts for 2023-11  in reddit_top_posts_by_month/2023-11.json
Saved 20 posts for 2023-12  in reddit_top_posts_by_month/2023-12.json
Saved 22 posts for 2024-01  in reddit_top_posts_by_month/2024-01.json
Saved 29 posts for 2024-02  in reddit_top_posts_by_month/2024-02.json
Saved 34 posts for 2024-03  in reddit_top_posts_by_month/2024-03.json
Saved 17 posts for 2024-04  in reddit_top_posts_by_month/2024-04.json
Saved 20 posts for 2024-05  in reddit_top_posts_by_month/2024-05.json
Saved 29 posts for 2024-06  in reddit_top_posts_by_month/2024-06.json
Saved 100 posts for 2024-07 in reddit_top_posts_by_month/2024-07.json
Saved 100 posts for 2024-08 in reddit_top_posts_by_month/2024-08.json
Saved 90 posts for 2024-09  in reddit_top_posts_by_month/2024-09.json

### Variable Description
**Each post object includes various fields that provide detailed information about the post. Below are the relevant fields I used in my dataset:**
*id*: Unique identifier of the post.
*title*: The title of the post.
*score*: The score of the post (upvotes minus downvotes).
*url*: The URL of the post.
*selftext*: The text of the post (if it is a text post).
*author*: The username of the person who posted.
*created_utc*: The creation time of the post in UTC. (ONLY IN past_year_top_posts_API_RAW_DATA.json)
*num_comments*: The number of comments on the post.

**Created Fields:** 
*created_date*: The creation time of the post in ISO 8601 format, converted from *created_utc*
*Rank*: The rank of the post ranging from 1-800 based on *score*

**UNUSED FIELDS from Reddit API:**
*upvote_ratio*: The ratio of upvotes to downvotes.
*subreddit*: The name of the subreddit where the post was made.
*subreddit_id*: The unique identifier of the subreddit.
*subreddit_subscribers*: The number of subscribers to the subreddit.
*permalink*: The permanent link to the post on Reddit.
*is_self*: Boolean indicating if the post is a self-post (text post) or a link.
*over_18*: Boolean indicating if the post is marked as NSFW (Not Safe For Work).
*is_original_content*: Boolean indicating if the post is marked as original content.
*stickied*: Boolean indicating if the post is stickied (pinned) at the top of the subreddit.
*locked*: Boolean indicating if the post is locked (no new comments can be made).
*gilded*: Number of times the post has been gilded (received awards).
*edited*: Boolean or timestamp indicating if the post was edited and when.
*link_flair_text*: The flair text assigned to the post (if any).
*spoiler*: Boolean indicating if the post is marked as a spoiler.
*hide_score*: Boolean indicating if the score is hidden.
*author_fullname*: The full identifier of the author (useful for user-specific data).
*thumbnail*: The URL of the post thumbnail, if available.

### Publisher
- Student project at RPI

### Contributors
- Tiziana Hernandez (Data Collector and Curator)

### Date
- **Creation Date**: 2024-09-17
- **Last Updated**: 2024-09-19

### Type
- **Type**: Dataset

### Format
- **Format**: application/json

### Identifier
- **Repository URL**: https://github.com/thernandez7/Reddit-Top-Posts-from-r-PoliticsSept-2023-Sept-2024

### Source
- Reddit API Documentation: https://www.reddit.com/dev/api
- PRAW Documentation: https://praw.readthedocs.io/en/stable/ 
- PRAW Submission Objects: https://praw.readthedocs.io/en/latest/code_overview/models/submission.html

### Language
- **Language**: English

### Rights
- **License**: N/A 
- **Rights Holder**: Tiziana Hernandez 

### Coverage/Scope
- **Geographical Coverage**: Global
- **Temporal Coverage**: September 18, 2023 – September 18, 2024
