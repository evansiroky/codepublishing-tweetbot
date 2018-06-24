# codepublishing-twitterbot
A twitter bot that tweets a section of the municipal code of a city

## Why?

This bot is inspired by other twitter bots such as [Every Lot Bot](https://twitter.com/everylotsf) and [Every Census Tract](https://twitter.com/everytract) which chronicle the built environment through pictures of lots and aerial images showing the spatial layout of the land.  This bot seeks to add to this story by chronicling the zoning laws of a particular city that shape what gets built.  

Furthermore, this github project seeks to provide a means to download codes and/or create other twitter bots that could tweet any subsection of a municipal code published at http://www.codepublishing.com/.

## How?

1.  The first step is to download all of the code to a local machine.  The `download.js` script takes in an argument of the root website and section of code that should be downloaded.
2.  Next, the `generate-tweets.js` script parses the downloaded files and creates a big list of tweets that should be sequentially published by the bot.
3.  The bot is to be published as an AWS Lambda service.  TODO: generate serverless deployment script / instructions

## Deployment(s)

This project is under construction, but once a twitter bot has been deployed, this section will be updated.
