## Twitter Interaction Dataset

This repository contains twitter datasets of tweet interactions of users. The interactions are stored as a bipartite graph of users and tweets (user_id, tweet_id, interaction_type). 
The dataset was crawled from the twitter API using the [twitter-crawler](https://github.com/philipphager/twitter-crawler) project.

## Interaction types
| Interaction | Id |
|-------------|----|
| Tweet (author) | 0 |
| Favorite | 1 |
| Retweet | 2 |
