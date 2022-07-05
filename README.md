# Statistic project - Inferential analysis
### A  hypothesis testing on goodread's personal book challenge.


__*Hypothesis testing is a form of inferential statistics that allows us to draw conclusions about an entire population based on a representative sample.*__

In this project, i am doing hypothesis tests to investigate and statistically test my assumptions about the personal book challenge on the website [Goodreads](https://www.goodreads.com).

*Brief context about the challenge:*<br>
On Goodreads website/apps, there is a feature to join the yearly reading challenge. In this challenge, the user can specify how many books they plan to read this year, and everytime the user mark a book as read in that year, it will be counted into the challenge. <br>
The user can see their previous challenges and other users' challenge.

![image](https://user-images.githubusercontent.com/78975611/177334021-3c0ed009-0456-4bbe-9318-ffddb30adf8f.png)

I have some assumptions that i would like to test, regarding why some people managed to complete the challenge they set themselves and some does not.

-----------------------------------------------

*Questions that i would like to answer:*
- Is there any correlation between genre preferences & the completion of the challenge?
- Are there any correlation between the reader's demographic (gender & age) and their preferred genre?
- Do readers who are more social more likely to complete the challenge?
- Do readers who prefer fiction books read more pages on average?
- Do readers who used the app more actively more likely to complete the challenge?

-----------------------------------------------


*Statistical tools i used:*
- chi2 contigency
- one way ANOVA test (f_oneway)
- t-test independent

-----------------------------------------------

*The data that i collected from goodreads users:*
- Gender
- No. of ratings 
- No. of reviews 
- Year joined
- Whether they are young ot not
- Location (continent)
- No. of friends
- No. of groups
- Favourite book genres
- Whether they completed the challenge or not (2018 - 2020)
- No. of average page they read per year (2018-2020)
