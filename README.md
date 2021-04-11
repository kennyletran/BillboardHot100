# BillboardHot100

The Billboard Hot 100 is the music industry standard record chart and has been a reliable source of music popularity rankings since its inception. Songs on the chart are ranked 1-100 by radio play, streams, record sales, and other impressions in descending order (the number 1 position represents the most popular song). 

There is a lot of appeal and incentive to enter and maintain a spot on the Billboard Hot 100. Artists want their music to be heard and label heads want to invest in popular artists. For this reason, many artists are attempting to optimize their music to maximize the amount of time their songs remain on the charts. We are interested in what audio features can influence chart longevity and how impactful those features are. 

This project seeks to answer the question: **Given that a song has made the Billboard Hot 100, what is the best regression model that predicts how long that song will continuously stay on the Billboard Hot 100.**

Our dataset consists of two sources: the Billboard Hot 100 Chart Data between 8/2/1958 and 12/28/2019 and Spotify audio features for each unique song obtained from the Spotify API. Our final dataset has a total of 28,474 unique songs (only songs that have entered the Billboard Hot 100 are considered).
