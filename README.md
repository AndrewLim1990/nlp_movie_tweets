# nlp_news_tweets

I'm working on [News360](https://news360.com/)'s NLP [test task](https://docs.google.com/document/d/1ziUlEDtOBChJzHvArc4GzQKJKG1s-Ut9IkzGAyzAdJI/edit#heading=h.o1egger9j1r), which is to write a data science pipeline that analyses tweets every ten minutes and sends a push notification when a big story breaks – but no more than twice per day.

My Twitter bot is now in testing, and it's viewable here: [https://twitter.com/news_nlp_bot](https://twitter.com/news_nlp_bot).

To test my script for yourself, feel free to clone this repo, set up a Twitter API, and type this in Terminal:

`watch -n 600 bash run_all.sh`

This will run the main script every ten minutes as long as you keep Terminal running.

## Progress

### Complete

- Write script to query the tweets from Twitter.
- Write script to identify tweets that are worthy of notification.
- Write bash script for the whole pipeline.
- Write script to notify users (by retweeting the selected tweet from the API's authenticated account).

### In progress

- Validate / tweak parameters.
- Write a blog post explaining my methodology.

### To do, later

- Add testing and package management.
- Add license.

