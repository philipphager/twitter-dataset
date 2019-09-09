# Retweet dataset

This dataset contains tweet and retweet interactions by users. Seed user for the crawl was [Neil deGrasse Tyson](https://twitter.com/neiltyson).

## Crawling strategy:
For each user:
1. Crawl up to 25 tweets from their timeline
2. For each tweet, add the tweet author and retweeters (up to 500) to the crawling queue.
3. Start over

In the end, all entries were deduplicated.

## Statistics
| Description | Stat |
|-------------|------|
| Number of users | 1,800,529 |
| Number of tweets | 1,711,584 |
| Number of tweet interactions | 7,233,955 |

## Interactions
| Interaction | Id |
|-------------|----|
| Tweet (author) | 0 |
| Favorite | 1 |
| Retweet | 2 |
