# beetle

This is an NLP model trained to combat individual roster move threads in a fantasy sport subreddit

## Scraping Data with PRAW

To obtain the data, scraping of the moderation log was performed using the [Python Reddit API Wrapper](https://praw.readthedocs.io/en/latest/). 

*Note: The `gather.ipynb` script is only meant to showcase the steps taken to scrape the requisite data using PRAW. The login info is stored separately on a locally hosted `praw.ini` file. You'll have to configure your own `praw.ini` file (with moderator privileges) because running the `gather.ipynb` script as is on your machine will not generate the .csv for you.*

