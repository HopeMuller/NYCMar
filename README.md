# NYC Marathon Project

Fifty-five years ago, the New York City Marathon had 55 finishers, and it has now grown to the world’s largest marathon, with 53,639 finishers in the 2019 race. People travel from all over the world to race, some running the entire 26.2 miles at a pace faster than I can run one mile. 

As a runner, I am intrigued by running trends and conclusions that I read about online. Some say that runners are getting faster over the years (Minsberg, 2020). But are they? I have read that men and females peak in their running times at specific ages (Zavorsky 2017). However, is that true? And what about cold and hot days? Journalists give definitive numbers on how someone’s mile-pace is affected by temperature changes on race day (Hosier, 2019). I looked more into these three topics. 

<strong>Research Questions</strong>

I considered three questions about New York City Marathon finishers. 

1. Has median race pace, subsetted by age, sex, and speed quartiles, changed over the years?

2. At what age do runners peak in their race pace? 

3. Do cold and hot race days impact runners’ race pace compared to average temperature race days?

<strong>Data</strong>

The New York Road Runners reports individual-level runner data on their public website. I used the RSelenium package in R to scrape runner data from several years of the race. The data set includes most runners (99% - 100%). The missing 0-1% is due to glitches in the scraping tool, server, or internet, during the scraping. In total, there were 461,163 runners in the dataset, with 68,874 of those runners repeating the race more than once. Of the repeat runners, 143 ran the race all thirteen years that I collected, 2001-2003 and 2009-2019.
