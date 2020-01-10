# RedditVeganism
A look at the plant-based trend on this website


## Motivation



The world is changing. Humans are always finding new ways to progress and push the world forward. As so, plant-based food consumption is growing FAST. Everywhere you go you see more and more meat and dairy alternatives. Vegans are on the rise, and for good reason. Animal agriculture is one of the biggest contributors to devastating climate change . The less we rely on this method of food production, the better off we are. Both our bodies and our planets are likely to be much healthier. The animals get to be animals too. Even if you don’t want to shift your diet closer to this lifestyle, there’s a lot of money to be made in this space if you have an eye for investments. Everybody can win here!

## Data Overview

The massive dataset consists of all the publicly available Reddit comments from 2005 - 2019. It was uploaded to Google's BigQuery by Felipe Hoffer, currently a developer advocate at Google. BigQuery is where I was able to run queries to get data subsets to work with. 


## Exploratory Data Analysis

One of the first things I wanted to do is check if comments containing the keyword "vegan" happened to grow in average score at a much higher rate than comments without that keyword. This might be an (admittedly weak) indicator that people on Reddit are growing in excitement about this lifestyle, and are more likely to upvote comments talking about it. 
![Average Score of Comments With the Word 'Vegan' in Them](vegscore.png?raw=true "Title")





## Hypothesis Testing


Ho = There is more overlap in commenters between r/Liberal and r/vegan than there is between r/vegan and r/Conservative

Ha = There is less overlap in commenters between r/Liberal and r/vegan than there is between r/vegan and r/Conservative

𝛼 = .01

Two sample t test:

P-value = 2.960313386996751e-15




## Conclusion

I reject the null hypothesis based on this simple experiment. There are a lot more vegan commenters on the liberal subreddit than the conservative subreddit. This is such a strong value because the conservative subreddit happens to have a lot more commenters in general than the liberal subreddit. In order to confirm this conclusion more experiments with a different design would be needed.

