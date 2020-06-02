# A Tale of Two Subreddits: Change and Continuity in Teaching-Related Online Spaces

## Abstract

Despite the ubiquity of social media in modern life, research on educators’ use of social media for professional purposes remains underdeveloped, especially regarding how this use may change, or remain the same, over time. This study explored change and continuity in two education-focused subreddits, r/Teachers and r/education, in terms of how users contribute, interact, and converse. In total, we collected more than a million contributions: 696,660 contributions to r/Teachers from 55,148 users and 339,618 contributions to r/education from 43,711 users, spanning a three-and-a-half-year time period. The affinity space concept framed multiple methods of analysis, including quantitative measures of individual contributions, content interactions, and social interactions, and qualitative content analysis of top posts and responses. Findings are discussed in light of the literature as well as potential implications for practice and future research.

## Data Collection

0. First, check to see the range of dates available for Reddit posts: https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_posts

**Collect subreddit posts:**

1. Go to: https://console.cloud.google.com/bigquery/

2. To collect all posts, in the `Query Editor`, paste in this script:

SELECT * FROM \`fh-bigquery.reddit_posts.20*\` WHERE subreddit = 'Teachers'

3. Run.

4. Save results >>> `CSV (Google Drive)`

**Collect subreddit responses:**

5. To collect all responses, in the `Query Editor`, paste in this script:

SELECT * FROM \`fh-bigquery.reddit_comments.20*\` WHERE subreddit = 'Teachers'

6. Run.

7. Save results >>> `CSV (Google Drive)`
