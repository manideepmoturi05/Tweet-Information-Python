# TwitterData
Get the tweet information with the tweet_Id using the twarc command

Twarc's hydrate command will read a file of tweet identifiers and write out the tweet JSON for them using Twitter's status/lookup API.

twarc hydrate ids.txt > tweets.jsonl

It will generate the tweets.jsonl file in which json format of the tweets with all the information is generated
