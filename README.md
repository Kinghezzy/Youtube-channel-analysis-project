# Youtube-channel-analysis-project
## Overview
This project provides a means to get a better insight into how users or viewers interract with videos posted on youtube and how a Youtuber can maximize the insight gotten from the data to provide more likeable content which will lead to improved metrics performance and more psoitive comments.

## The Aim of this project is to:
- Analyse the metrics of a video in a channel to know which metrics matters most. Metrics like number of comments, number of likes, number of views, video duration etc. Some questions answered include: 
Which video has the most views?
What does the view distribution per video look like?
‌Which particular day of the week are videos uploaded the most?
‌Which is a predictor of more views between likes and comments?
What is the video count based on duration?

- Carry out sentiment analysis on the overall comments in the channel as well as on each comment per video. This is aimed at deducing the level of positivity, neutrality or negativity of the comments which could indicate the level of satisfaction gotten by viewers of such videos. 

## Data source:
The data is gotten by interacting with youtube api and making requests. However, it should be noted that the documentation of youtube api ought to be understood in order to successfully  get the right data without errors. Also, it is note worthy to state that the insight into some parts of this analysis was gotten from The Vu Analytics channel on youtube.

## Limitations
- This project is just an analysis on one youtube channel and should not be used to draw conclusions on the contents from other channels.
- The comments used for the sentiment analysis are limited to twenty (20) comments for each video, based on the results gotten from the API which may skew the result of the sentiment analysis.
- The VADER model used in the sentiment analysis does not take into account the relationship between words, hence, might lead to inaccurate sentiments.

## Conclusions
From the analysis, we figured out that:
  1) The video on data analysis project has the highest views which could mean more people are now interested in data analysis
  2) Alex the analyst uploads videos mostly on Tuesdays than any other day.
  3) Most videos have an average of 300,000 views with some above and others beneath that value.
  4) The positive comments on the videos far outweigh the neutral and negative comments.

## Future Improvements
- Analyze more data to give more insight to answer questions like:
  1) Does duration matter?
  2) Does the number of tags affect other metrics?
  3) Does the time of upload affect the other metrics?
  4) Are the certain words on the title that lead to more views?
  so many questions....
- Use a more robust model for sentiment analysis
- Investigate if the result of the sentiment analysis actually match the reality.
