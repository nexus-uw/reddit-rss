reddit-rss
==========

[reddit post explaining what this is](https://www.reddit.com/r/rss/comments/fvg3ed/i_built_a_better_rss_feed_for_reddit/)

## installation
Your options are `docker build .` or `go build .`.

## exposed ports
- 8080 (HTTP)

## query params
- `?safe=true` filter out nsfw posts
- `?limit=100` filter out posts with less than 100 up votes
