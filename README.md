# Topic modeling on "Russian troll tweets"

Using the [tweet corpus]((https://github.com/fivethirtyeight/russian-troll-tweets) provided by fivethirtyeight, we perform topic modeling on the tweets.

Topic modeling may not be well suited for short-form texts such as tweets,
however the top results could still be interesting.

Another approach will be to use sentiment analysis with VADER.

---

>This directory contains data on nearly 3 million tweets sent from Twitter handles connected to the Internet Research Agency, a Russian "troll factory" and a defendant in [an indictment](https://www.justice.gov/file/1035477/download) filed by the Justice Department in February 2018, as part of special counsel Robert Mueller's Russia investigation. The tweets in this database were sent between February 2012 and May 2018, with the vast majority posted from 2015 through 2017.

_(more on the data source here: [https://github.com/fivethirtyeight/russian-troll-tweets](https://github.com/fivethirtyeight/russian-troll-tweets))_



The files have the following columns:

Header | Definition
---|---------
`external_author_id` | An author account ID from Twitter
`author` | The handle sending the tweet
`content` | The text of the tweet
`region` | A region classification, as [determined by Social Studio](https://help.salesforce.com/articleView?id=000199367&type=1)
`language` | The language of the tweet
`publish_date` | The date and time the tweet was sent
`harvested_date` | The date and time the tweet was collected by Social Studio
`following` | The number of accounts the handle was following at the time of the tweet
`followers` | The number of followers the handle had at the time of the tweet
`updates` | The number of “update actions” on the account that authored the tweet, including tweets, retweets and likes
`post_type` | Indicates if the tweet was a retweet or a quote-tweet
`account_type` | Specific account theme, as coded by Linvill and Warren
`retweet` | A binary indicator of whether or not the tweet is a retweet
`account_category` | General account theme, as coded by Linvill and Warren
`new_june_2018` | A binary indicator of whether the handle was newly listed in June 2018


### NOTE:
>If you use this data and find anything interesting, please let us know. Send your projects to oliver.roeder@fivethirtyeight.com or [@ollie](https://twitter.com/ollie).

