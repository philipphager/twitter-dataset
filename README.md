# Twitter Interaction Dataset
## Abstract
This repository contains datasets we use to evaluate the implementation of the [kafka-salsa](https://github.com/torbsto/kafka-salsa) project. Kafka-salsa is an in-memory, graph-based tweet recommender system implemented on [Kafka-Streams](https://kafka.apache.org/documentation/streams/), which uses an interaction graph (e.g., likes, writes, retweets) between users and tweets to recommend new tweets to a given user. We crawled our own bipartite graph dataset of user-tweet-interactions to evaluate the performance and quality of different implementation approaches. This repository contains our dataset, which we crawled from the Twitter API using our [twitter-cralwer](https://github.com/philipphager/twitter-crawler) project. The dataset is a CSV in form of `user_id, tweet_id, interaction`. Find the full documentation, evaluation metrics and results in the central repository [kafka-salsa](https://github.com/torbsto/kafka-salsa). Find a description of the dataset and our crawling strategy inside the [dataset README](https://github.com/philipphager/twitter-dataset/blob/master/v1/README.md).

## Repository Overview
This repository is part of a larger project. Here is a list of all related repositories:
* [kafka-salsa](https://github.com/torbsto/kafka-salsa): Reference implementation and project documentation.
* [kafka-salsa-evaluation](https://github.com/philipphager/kafka-salsa-evaluation): Evaluation suite for [kafka-salsa](https://github.com/torbsto/kafka-salsa).
* [twitter-cralwer](https://github.com/philipphager/twitter-crawler): Twitter API crawler for user-tweet-interaction data.
* [twitter-dataset](https://github.com/philipphager/twitter-dataset): Crawled datasets of user-tweet-interactions used in evaluation.

## Installation
1. Clone the repository: `git clone git@github.com:philipphager/twitter-dataset.git` or download individual files directly from Github.
2. If you use the dataset to evaluate kafka-salsa, please see the instructions at [kafka-salsa-evaluation](https://github.com/philipphager/kafka-salsa-evaluation).
