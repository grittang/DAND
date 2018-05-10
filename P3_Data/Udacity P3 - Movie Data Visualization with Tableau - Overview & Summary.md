# Movie Data Visualization with Tableau

by Grit, 2018.02

## 1. Overview

In this project, we'll explore data from *The Movie Database* to draw out and display interesting patterns. Let's start by defining some leading questions:

> Question 1: How have movie genres changed over time? (Budgeted over $100m)
>
> Question 2: How do the attributes differ between Universal Pictures and Paramount Pictures? (Budgeted over $100m)
>
> Question 3: How have movies based on novels performed relative to movies not based on novels? (Budgeted over $100m)
>
> Question 4: What's The Relationship Between Profitability And Ratings? (Budgeted over $100m)

Then we'll explore the data to find answers, which will be all displayed by dashboards. 

For Q4, in addition to creating a dashboard, we'll create a narrative told through visualizations and text using Tableau Stories feature.



## 2. Data Wrangling with Pandas, NumPy and IPython
The raw data should be handled with Python modules and packages:

- Dealing with duplicates
- Removing the 'Unnamed' columns
- Normalizing the data types and formats
- Comparing the two "release" columns to make them match
- Handling the Null/NA/Zero values
- Saving the tidy dataset as a CSV file 

[Here is the codes for data cleanup.](https://github.com/grittang/DAND/blob/master/P3_Data/DAND%20P3%20-%20Movies%20Data%20Visualization.ipynb)


## 3. Data Visualization with Tableau

The following pictures are our dashboards and story. You can check the [on-line Tableau dashboard](https://public.tableau.com/profile/grit#!/) or download the [original Tableau file](https://github.com/grittang/DAND/blob/master/P3_Data/DAND%20P3%20-%20Movies%20Data%20Visualization.twbx) for more details. However, the layout of Question 1 dashboard may be disorganized, and the layout from the [original Tableau file](https://github.com/grittang/DAND/blob/master/P3_Data/DAND%20P3%20-%20Movies%20Data%20Visualization.twbx) is okay.



## 4. Summary

The answers to each question, which have been embedded in the charts, will be listed as follows:

##### Question 1: How have movie genres changed over time? (Budgeted over $100m)

> - The 5 most popular genres are Drama, Comedy, Thriller, Action and Adventure, and the percentage of total is 60%. Among the top genres, Drama is always the most popular one, with the average percentage of 17%.
> - Clearly for all genres, Q1 is the weakest of the year, followed by a full rise in Q2, with some genres, such as Action and Adventure, reaching their peak. Then the differences come out in Q3, which is the outbreak period for Thriller, but a growth period before the next for Drama. However, on the whole, Q3 is still the prime of the year with a slight advantage over Q4.

##### Question 2: How do the attributes differ between Universal Pictures and Paramount Pictures? (Budgeted over $100m)

> - Both studios have shown growth in production, despite the lack of stability in the early years. However, Universal Pictures has got a bit advantage over its rival since around 2005. 
> - The movies, located in whether "In - Top Genres" or "Out- Top Genres", bring Paramount Pictures higher median profit.

##### Question 3: How have movies based on novels performed relative to movies not based on novels? (Budgeted over $100m)

> - Compared with movies not based on novel, although the number of movies adapted is only 5% of the latter, the average rating is 0.3 higher, and the median profit is actually 31% higher than the latter.
> - In almost all genres, except for comedies, the movies adapted from novels have a higher median proifit.

##### Question 4 - Story: What's The Relationship Between Profitability And Ratings? (Budgeted over $100m)

> - The median or average rating is 6.2. The median profit of profitable movies is $66.24m.
> - The Pearson correlation between the ratings and profits is 0.26, implying a weak positive linear relationship between the two variables.
> - Among the non-profitable movies, the movies above the average rating accounts for 68%, twice the size of ones not higher than the average rating. And the top grossing movies with more than $800m, basically have a rating above the average.
> - 27% of releases are in the "High Profits, High Ratings" category, but they make up 67% of profit.

  

















[<center>![Data Source](https://www.themoviedb.org/static_cache/v4/logos/312x276-primary-green-74212f6247252a023be0f02a5a45794925c3689117da9d20ffe47742a665c518.png)</center>](https://www.themoviedb.org/?language=en)