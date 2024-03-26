### Check out my project over [here](https://sabinahung.github.io/dumpster-dive/)!

## Goal 
This project was initially set to find out whether dumpster diving is on the rise by looking at the numbers of videos over the years on YouTube.
## Findings
Vidoes on dumpster diving peaked in 2023
## Data collection 
This project requires some wrangling with YouTube API and it hasn't been easy to figure out how to use it. This is my second try attempting to understand how it works. Thankfully, some friendly dude on YouTube posted this [tutorial](https://www.youtube.com/watch?v=th5_9woFJmk&t=398s) that walks you through step by step on how to use YouTube API with Python.

After understanding how to query the API, another thing to be mindful of was the daily quota you have each day to request for info from the API. I realized much later working on this project that the quota you have left seem to affect the amount of information you could get out of the API. It's embarrassing but you could check the error code in my `youtubeAPI.ipynb` for reference. It returns different number of total result whenever I move on to the next page of the results.
## Data analysis 
After saving the information I need to a dictionary, I sieve through them with `str.contains`. (It is also about when I realize things might look a little sus.)

## What I learned
- Technical:
  - YouTube API
- Risk management:
  - Reach out early for help! It could be help from YouTube tutorials or just people you've known who wrangled with the tool you're using.
  - Go back and forth between reporting and data wrangling!  

