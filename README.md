### twitteR Overview

[Twitter](http:twitter.com) is a massive online social networking microblogging service that allows users to post short messages (“tweets”) that are 280 characters long. Across the years, this has been not only a unique form of social media, but also assists those users interested in data mining experiments. Within the twitteR package, users are provided access to the Twitter API within R, enabling them to subset certain Twitter data for analyses.



<img src="https://logos-download.com/wp-content/uploads/2016/02/Twitter_Logo_new.png" alt="The rmarkddown hex sticker" align="right" width="200" style="padding: 0 15px; float: right;"/>

### Installation

In order to install the **twitteR** package within RStudio is to firstly install [RStudio](http://rstudio.com/products/rstudio/download/preview). RStudio enables you to use different functions in R.

Within RStudio, you can install the package by:

```r
install.packages("twitteR")
```

twitteR uses a few other packages in order for you to use its functions such as:

```r
install.packages("httr")
install.packages("openssl")
install.packages("RSQLite")
```

To begin using Twitter's API, one must create a Twitter account and register for a [Developer Account](http://developer.twitter.com/en/apply-for-access). From there, users must fill out an application to gain permission to access Twitter's API. After creating a Developer Twitter Account, go on the [Apps Tab](https://dev.twitter.com/apps) and click **Create New App** and fill out the necessary information. After granted permission to use Twitter's API, users will be able to access Twitter's API under their **Keys and tokens** tab. Users will be given a unique Consumer API Key, a unique Consumer Secret Key, a unique Access Token Key, and a unique Access Token Secret. 

For example, a sample randomly generated key looks like:
```r
consumer_key <- "2GCWgA9HRyAFWHXw79n3kWDi7"
consumer_secret <- "yHLdijkMkY9GIzMXKE7kuyHWBdEIgSBcwPvm9q3eaDo2GLql9z"
access_token <- "1445559278-eLFn9SDtm8SCrkxY37WlC7wxZACx9Sjyfv0z8dc"
access_secret <- "2E4mbtdqYIAfy3BKPt7Wu8M4n5zil3rVTGdQL6QDbGasp
```

After retrieving the keys, use the function:

```r
setup_twitter_oauth(consumer_key, consumer_secret, access_token, access_secret)
```

Hopefully this is enough to get you started in using the twitteR package!
