### twitteR Overview
Twitter Vignette R Project

Twitter is a massive online social networking microblogging service that allows users to post short messages (“tweets”) that are 280 characters long. Across the years, this has been not only a unique form of social media, but also assists those users interested in data mining experiments. Within the twitteR package, users are provided access to the Twitter API within R, enabling them to subset certain Twitter data for analyses.

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

To begin using Twitter's API, one must create a Twitter account and register for a [Developer Account](http://developer.twitter.com/en/apply-for-access). 
