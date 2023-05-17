# p1big_data_bandits

PROCESS AND ASSIGNMENTS
- We cleaned the raw dataset in the wine.ipynb file together live, so that we agreed on which columns and null values to remove that we wouldn't need in our analysis. 
- From there, each team member was assigned initial questions and queries we agreed would be interesting to explore. These questions and topics evolved as we each started coding, either realizing that what we initially thought we could analyze in the data can't be done (e.g. correlations between integers and strings), or discovering new subsets of questions based on initial findings. 
- Each of our individual codes as in files titled [team_member_initials]_wine.ipynb. As such, we each wrote our own analysis based on our individual codes below, so that it's easier to follow along.

RUTVA KORAT ANALYSIS (rk_wine.ipynb)



ELENA LUCHERINI ANALYSIS (el_wine.ipynb)
Examine number of ratings per wine variety:
The top most rated wine types all have at least 2,700 reviews, with the most-rated wine variety being Pinot Noir with 12,785 reviews. As evidenced by the bar chart, there's a fairly even spread between red wines and white wines, with only rose wine included in the top 10.

Deeper Dive into California Wine Types:
It is clear that out of all the California bottles reviewed, the largest percentage were Pinot Noir, which aligns to the analysis that Pinot Noir wines were the most reviewed wine type across the dataset, in conjunction with California wines being the most reviewed as well. However, it's also clear based on the pie chart that California produces a myriad of wine varieties (193 in total, in fact), and while Pinot Noir makes up the lion's share, it is certainly not the majority. 

Correlation between sommeliers' number of ratings and average wine rating and/or average wine price:
The 19 sommeliers that reviewed the wines in the dataset generally had very similar averages and medians in their ratings. None of the sommeliers gave a rating below 80 (out of 100), and four rated wines at 100. When looking at the correlation between the number of ratings per sommelier and the average wine rating (out of 100), the correlation coefficient is 0.28. Since this is not close to either 1 or -1 to suggest a perfect correlation, this indicates that the number of reviews that a sommelier has completed does not correlate to the rating they prescribe.

The same cannot be said for each sommelier's range in wine prices. The highest wine price at $3,300 was reviewed by Roger Voss, with the second highest price of $2,013 reviewed by Matt Kettmann. Many of the reviewers, including Roger Voss and Matt Kettmann, rated wines below $10, suggesting that these sommeliers are not necessarily picky about the price of the wines they review. That said, the correlation coefficient between the number of ratings and the average wine price is 0.51. While this still isn't a perfect correlation, it does suggest that there is a slight pattern that the more wines one reviews, the most expensive the average price per bottle. There are a number of reasons why this might be, such as perhaps wineries with more expensive bottles prefer to be reviewed by sommeliers with more experience. 

Deeper Dive into Sommelier Roger Voss:
We decided to specifically analyze Roger Voss' data, the sommelier who reviewed the most number of wines (20K+), as well as reviewed the most expensive bottle ($3,300). In calculating the correlation between rating and bottle price in his entire dataset, the coefficient is 0.41, suggesting that there is a slight, but not very strong, correlation between the price of the bottle and the rating he gives that bottle. 

In trying to determine which wines might be outliers based on price, we discovered that the interquartile range is too small, and many of the bottles would be considered outliers. As such, the box and whiskers graph was illegible and unhelpful in our analysis. 

We then took a smaller sample of 50 of Roger Voss' data, which yielded a correlation of 0.51 (as of 5/16/2023). This is not too dissimilar to the entire Roger Voss dataset correlation of 0.41, and therefore we deem that the sample is appropriate. We also found the scatter chart of the sample size more legible than the entire dataset. 

Sommeliers and Twitter:
There was not much analysis we felt was necessary regarding the sommeliers and their Twitter handle information. We found that most of the sommeliers (84%) have public twitter accounts, and only 3 do not.


ADAM NGUYEN ANALYSIS (an_wine.ipynb)



ANDREA PAREDES ANALYSIS (ap_wine.ipynb)


