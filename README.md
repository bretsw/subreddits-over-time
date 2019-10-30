# r-teachers
Study of the r/Teachers subreddit over time - https://www.reddit.com/r/Teachers/



## Data Collection

1. Go to: https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments
2. Choose “Try the new UI”
3. Paste in script for comments:

SELECT * FROM \`fh-bigquery.reddit_posts.20*\` WHERE subreddit = 'Teachers'

4. Open `More >>> Query settings` and selected `SQL dialect = Standard`
5. Run.
6. Save results >>> `CSV (Google Drive)`
7. Paste in script for posts:

SELECT * FROM \`fh-bigquery.reddit_posts.20*\` WHERE subreddit = 'Teachers'

8. Save results >>> `CSV (Google Drive)`
