# twitter_us-election-polls_2016-2020
Repository containing data of US election polls published on Twitter in 2016 and 2020. We seperate tweet ids into the following files:
- **tweet_ids_2016.json:** contains tweet ids for polls crawled during the 2016 U.S Presidential Election cycle. Does not contain author ids, follower ids, etc. 
- **tweet_ids_2020.json:** contains tweet ids for polls crawled during the 2020 U.S Presidential Election cycle. Does not contain author ids, follower ids, etc. 

Each file is structured as,
```
{
    "vote" : [tweet_id_1, tweet_id_2, ... tweet_id_n],
    "voting" : [tweet_id_n+1, tweet_id_n+2, ..., tweet_id_n+k] 
}
```
Where the ids corresponding to the "vote" list are those tweet ids associated with polls collected via the "vote" query. 