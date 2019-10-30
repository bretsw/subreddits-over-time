# r-teachers
Study of the r/Teachers subreddit over time - https://www.reddit.com/r/Teachers/



## Data Collection

1. Go to: https://console.cloud.google.com/bigquery/

**Collect subreddit posts:**

2. To collect all posts, in the `Query Editor`, paste in this script:

SELECT * FROM \`fh-bigquery.reddit_posts.20*\` WHERE subreddit = 'Teachers'

3.  Run.
4. Save results >>> `CSV (Google Drive)`

**Collect subreddit responses:**

5. To collect all responses, in the `Query Editor`, paste in this script:

SELECT * FROM \`fh-bigquery.reddit_comments.20*\` WHERE subreddit = 'Teachers'

6. Run.
7. Save results >>> `CSV (Google Drive)`
