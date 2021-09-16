# Repository for qualitative survey performed as part of the article "The impact of the Covid-19 cases with Twitter users in their perception of the Brazilian government"

## Dataset
This dataset includes a CSV file containing tweet ids and sentiments attributed to the tweets automatically, using the VADER tool, and manually using a qualitative survey performed as part of the article “The impact of the Covid- 19 cases with Twitter users in their perception of the Brazilian government”.

## Twitter policy restricts
We respect the [content redistribution policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy) required by Twitter. Twitter policy restricts Twitter dataset sharing to Ids only. Therefore, tweet IDs are the only information contained in the tweets provided in this dataset.
> You need to hydrate tweet IDs to get complete data. Hydration of the Ids can be performed using [Hydrator](https://github.com/DocNow/hydrator), a software developed and made available by [DocNow](https://www.docnow.io),  a community that supports ethical preservation of social media content.

## How this dataset is organized

- File name : [qualitative_research.csv](https://github.com/juniori/covid19_users_perception_qualitative_research/blob/main/qualitative_research.csv)
- Number of evaluators: 14
- Number of evaluations: 650
- Fields:

  - **tweet_id** : Unique identifier of the tweet;

  - **vader_sentiment_subcateg** : Sentiment assigned using the VADER tool;

  - **manual_sentiment_subcateg**: Sentiment assigned manually using a qualitative research;

  - **flag** : Indicates if the tweet is part of the group before or after the base tweet (D=After base tweet ,A=Before base tweet );

  - **evaluator** – The evaluator's identifier code.
```
