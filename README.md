
### Udacity Data Analyst Nano Degree ###
### Project 04 - Wrangling and Analyze Data ### 

#### Columns ####
#### Downloaded data by WeRateDogs page ####

- `tweet_id` Tweet ID  
- `in_reply_to_status_id` Removed column
- `in_reply_to_user_id` Removed column
- `timestamp` Day / Month / Year / Hour / Minute / Second of the tweet
- `source` Url where the tweet was made
- `text` Text of the tweet
- `retweeted_status_id` Removed column
- `retweeted_status_user_id` Removed column
- `retweeted_status_timestamp` Removed column
- `expanded_urls` Removed column
- `rating_numerator` Must be greater or equal to 10 ("they're good dogs Brent")
- `rating_denominator` Must be equals to 10
- `name` Name of the dog (taken from the text)
- `doggo` Dog stages (see the "dogtionary")
- `floofer` Dog stages (see the "dogtionary")
- `pupper` Dog stages (see the "dogtionary")
- `puppo` Dog stages (see the "dogtionary")

#### Data Downloaded programmatically ####
- `tweet_id` Tweet ID  
- `jpg_url` Url with the dog photography
- `img_num` How many dog photographies in a single tweet
- `p1` is the Udacity Neural Network Algorithm's #1 prediction for the image in the tweet
- `p1_conf` is how confident the algorithm is in its #1 prediction
- `p1_dog` is whether or not the #1 prediction is a breed of dog
- `p2` is the Udacity Neural Network Algorithm's #2 prediction for the image in the tweet
- `p2_conf` is how confident the algorithm is in its #2 prediction
- `p2_dog` is whether or not the #2 prediction is a breed of dog
- `p3` is the Udacity Neural Network Algorithm's #3 prediction for the image in the tweet
- `p3_conf` is how confident the algorithm is in its #3 prediction
- `p3_dog` is whether or not the #3 prediction is a breed of dog

#### Tweeter API downloaded JSON data file ####
- `tweet_id` Tweet ID
- `retweet_count` How many times a tweet was retweeted
- `favorite_count` How many times a tweet was added as favorite