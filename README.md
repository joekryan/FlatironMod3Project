# Movie Database Project
The aim of this project was to answer 2 business questions:
* What is the most popular genre of movie?
* When is the best time to release a movie?

For more information, please see the presentation.pdf file

## Methods Used

To gather the data, we first connected to the Movie Database API, downloaded data for films released in 2018 in two datasets then erged both datasets into a csv
We focused analysis on two dependent variables: average voter rating and revenue


To test these hypotheses we used the following methods: 

- Null Hypothesis
- T-test
- ANOVA
- Cohen's D
- Mann Whitney U Test
- Tukey Test
- Kruskal Wallis Test
- QQ Plots

## Results

<p align="left">
  <img src="https://github.com/joekryan/movie_database_project/blob/master/images/dramedy.png">
</p>
We found that the movie genre with the highest rating is Drama. We also found that non-English language movies have significantly higher ratings, however the effect size is tiny (Cohen's D = 0.23).


<p align="left">
  <img src="https://github.com/joekryan/movie_database_project/blob/master/images/day.png">
</p>
We also found that although the quarter and month of release has no significant effect on a movie's revenue, the day on which it is released does. Movies released on Wednseday have a significantly higher revenue than movies not released on Wednesday /

## Conclusion

For a movie that is most likely to be highly rated and have high revenues, release a drama film on a Wednesday!
