# p1big_data_bandits

PROCESS AND ASSIGNMENTS
- We cleaned the raw dataset in the wine.ipynb file together live, so that we agreed on which columns and null values to remove that we wouldn't need in our analysis. 
- From there, each team member was assigned initial questions and queries we agreed would be interesting to explore. These questions and topics evolved as we each started coding, either realizing that what we initially thought we could analyze in the data can't be done (e.g. correlations between integers and strings), or discovering new subsets of questions based on initial findings. 
- Each of our individual codes as in files titled [team_member_initials]_wine.ipynb. As such, we each wrote our own analysis based on our individual codes below, so that it's easier to follow along.
- While we each added our graphs and main points to the slide presentation, Rutva did the majority of the formatting and stylization. Link to slide deck here: https://docs.google.com/presentation/d/1P_9nebzgNoi1qimZPD-XADHueEfawLxfIaZdTpW6NCM/edit?usp=sharing


RUTVA KORAT ANALYSIS (rk_wine.ipynb)
In this dataset we have about 120,000 row of data on wines that have been reviewed by wine sommeliers and connoisseurs.
Within this dataset we came to know that there are 691 different types of wine that have been reviewed. Within those types of wines we were able to determine how many reviews each type of wine had. In our findings we were able to determine that some types of wine had thousands of reviews while other types only had one review. We decided to look into the 10 most rated wine types to see if there is a relationship between its pricing and rating. We wanted to know if the pricing of the bottle of wine that had been reviewed has any effect on its rated score. 

Here we took the top ten wine types that had the most ratings and decided to find the correlation of price to rating of each of them. The bar chart titled “Correlation Between Price and Rating by Top 10 Wine Types” show cases the correlation of each grouping of wine type from the top ten wines types. We can see here that Cabernet Sauvignon has the highest correlation and Rosé had the least correlation when comparing the pricing to their ratings. Overall we can determine that none of the top ten wine types have a strong correlation of pricing to rating. We can say that Cabernet Sauvignon has the highest correlation compared to the rest of the top wine types rated. Cabernet Sauvignon’s that have been rated in this dataset have a correlation of 0.556 which is considered as a moderate correlation while Rosé that have been reviewed in this data set have a weaker correlation of 0.262. From the top ten types of wine reviewed we have an overall correlation of 0.404 which is also considered as less than moderate correlation. With this we can state that out of the top wines rated from this dataset the rating is given moderately to the wines price points. 


ELENA LUCHERINI ANALYSIS (el_wine.ipynb)
The top most rated wine types all have at least 2,700 reviews, with the most-rated wine variety being Pinot Noir with 12,785 reviews. As evidenced by the bar chart, there's a fairly even spread between red wines and white wines, with only rose wine included in the top 10.

In taking a deeper dive into California wine types, it is clear that out of all the California bottles reviewed, the largest percentage were Pinot Noir, which aligns to the analysis that Pinot Noir wines were the most reviewed wine type across the dataset, in conjunction with California wines being the most reviewed as well. However, it's also clear based on the pie chart that California produces a myriad of wine varieties (193 in total, in fact), and while Pinot Noir makes up the lion's share, it is certainly not the majority. 

In looking at the sommeliers' data, the 19 sommeliers that reviewed the wines in the dataset generally had very similar averages and medians in their ratings. None of the sommeliers gave a rating below 80 (out of 100), and four rated wines at 100. When looking at the correlation between the number of ratings per sommelier and the average wine rating (out of 100), the correlation coefficient is 0.28. Since this is not close to either 1 or -1 to suggest a perfect correlation, this indicates that the number of reviews that a sommelier has completed does not correlate to the rating they prescribe. The same cannot be said for each sommelier's range in wine prices. The highest wine price at $3,300 was reviewed by Roger Voss, with the second highest price of $2,013 reviewed by Matt Kettmann. Many of the reviewers, including Roger Voss and Matt Kettmann, rated wines below $10, suggesting that these sommeliers are not necessarily picky about the price of the wines they review. That said, the correlation coefficient between the number of ratings and the average wine price is 0.51. While this still isn't a perfect correlation, it does suggest that there is a slight pattern that the more wines one reviews, the most expensive the average price per bottle. There are a number of reasons why this might be, such as perhaps wineries with more expensive bottles prefer to be reviewed by sommeliers with more experience. 

We decided to specifically analyze Roger Voss' data, the sommelier who reviewed the most number of wines (20K+), as well as reviewed the most expensive bottle ($3,300). In calculating the correlation between rating and bottle price in his entire dataset, the coefficient is 0.41, suggesting that there is a slight, but not very strong, correlation between the price of the bottle and the rating he gives that bottle. In trying to determine which wines might be outliers based on price, we discovered that the interquartile range is too small, and many of the bottles would be considered outliers. As such, the box and whiskers graph was illegible and unhelpful in our analysis. We then took a smaller sample of 50 of Roger Voss' data, which yielded a correlation of 0.51 (as of 5/16/2023). This is not too dissimilar to the entire Roger Voss dataset correlation of 0.41, and therefore we deem that the sample is appropriate. We also found the scatter chart of the sample size more legible than the entire dataset. 

There was not much analysis we felt was necessary regarding the sommeliers and their Twitter handle information. We found that most of the sommeliers (84%) have public twitter accounts, and only 3 do not.


ADAM NGUYEN ANALYSIS (AN_wine_country_region.ipynb)
With the data provided, we were able to determine that wine that originated from the United States received the most reviews (44.9% or 54,265 reviews). The next 2 countries to receive the highest were France (14.7% or 17,776 reviews) and Italy (14.0% or 16,914 reviews). Aside from the 3 countries the rest of the countries only account for 5.4% or less of the reviews by country. 

Digging deeper, we noticed that 4 states in the United States still accounted for top 10 in amounts of reviews. California accounted for 36,104 of the 54,265 reviews in United States, while the next state that was even considered close was Washington State with 8,583 reviews.

Lastly, we were able consolidate the data to show the top 3 bottle ratings within each Province, using longitude and latitude gathered by API, to show on a map.


ANDREA PAREDES ANALYSIS (ap_wine.ipynb)
While looking into the price of wine reviewed distribution, we could see that over ninety percent of reviews relate to wines priced under $500 dollars. In this DataSet, the wines with higher prices were produced in France and the US.
This analyses include wines produced in a total of 42 countries, with prices that varies from $4 dollars to $3,300 dollars per bottle.

While comparing the ratings and the price per bottle we can see that most wines with lower prices received good rating. We also noticed that the bottle with the highest price in this DataSet, received a lower rating.
