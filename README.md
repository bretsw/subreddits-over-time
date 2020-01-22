# subreddit-comparison

Study of the r/Teachers and r/education subreddits over time

https://www.reddit.com/r/Teachers/

https://www.reddit.com/r/education/

## Data Collection

0. First, check to see the range of dates available for Reddit posts: https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_posts

**Collect subreddit posts:**

1. Go to: https://console.cloud.google.com/bigquery/

2. To collect all posts, in the `Query Editor`, paste in this script:

SELECT * FROM \`fh-bigquery.reddit_posts.20*\` WHERE subreddit = 'Teachers'

3.  Run.
4. Save results >>> `CSV (Google Drive)`

**Collect subreddit responses:**

5. To collect all responses, in the `Query Editor`, paste in this script:

SELECT * FROM \`fh-bigquery.reddit_comments.20*\` WHERE subreddit = 'Teachers'

6. Run.
7. Save results >>> `CSV (Google Drive)`
