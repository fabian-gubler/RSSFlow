# RSSFlow: RSS Blog Aggregator

RSSFlow is a RSS feed aggregator built in Go! It's a web server that allows clients to:

- Add RSS feeds to be collected
- Follow and unfollow RSS feeds that other users have added
- Fetch all of the latest posts from the RSS feeds they follow

## Personal Learning Goals

- Learn how to integrate a Go server with PostgreSQL
- Learn about the basics of database migrations
- Learn about long-running service workers

## Setup

Create a gitignore'd .env file in the root of your project and add the following:

`PORT="8080"`

This file will automatically be loaded using `godotenv.Load()` in the main function.