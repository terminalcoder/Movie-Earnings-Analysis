# Movie Earnings Analysis

**Author**: Elimelech Berlin  
**Date:** December 2022

## Overview

This report analyzes available movie data to identify several aspects of successful films. The data used for this analysis includes information about movie earnings and other aspects of those films. By analyzing this information, several actionable insights for producing successful movies are revealed.


## Business Problem

As not all movies are created equal, producing the 'right' type of movie can be a tricky thing. There are a variety of factors that can influence the success and profitablity of a release; these factors are not always apparent. By analyzing available data about a large number of movies (both successful and unsuccessful), we can identify how certain factors impact the earnings of a film. In this report I aim to examine how movie genre and language impact movie profitability.


## Data

I will be using data from these two files: [im.db.zip](./zippedData/im.db.zip) and [bom.movie gross.csv.gz](./zippedData/bom.movie_gross.csv.gz).  
They contain data from the following movie data websites: 
* [Box Office Mojo](https://www.boxofficemojo.com/ 'https://www.boxofficemojo.com/')
* [IMDB](https://www.imdb.com/ 'https://www.imdb.com/')
* [Rotten Tomatoes](https://www.rottentomatoes.com/ 'https://www.rottentomatoes.com/')
* [The Movie DB](https://www.themoviedb.org/ 'https://www.themoviedb.org/')
* [The Numbers](https://www.the-numbers.com/ 'https://www.the-numbers.com/')

Included in this data is both business information and creative/content information. I will be focusing on some of the business data (earnings) but with an understanding of how it's influenced by other data (genre, producer age).



## Methods

In this report I use descriptive analytics to understand how movie genre and movie revenue are related. I also examine the apparent affect of language and the age of a given movies producer on its earnings. For most of my analysis I use information about mean earnings to get a sense of what movies in a particular category earned.


## Results
### Genre Analysis
![genre](images/earnings_by_genre_barh.png)
* Certain movie genres are more profitable than others.

***
### Languges Analysis
![languages](images/mean_earnings_by_lang_foreign_barh.png)  
* Films released in certain languages earn more money than films in other languages.


***
### Producer Age Analysis
![producer](images/mean_earnings_age_group_bar.png)
* The earnings of a movie increase as the age of its producer increases, as long as the producer is under seventy years old. 


## Conclusions

Three recomendations based on the above analysis are:
* Movies produced should be in one of the top genres for earnings. (Publishing movies of only the highest earning genre doesn't seem like a great idea for a company's reputation; it seems dull & unexciting & may drive away business.)  
The 5 highest earning genres are (in order of descending profitability):
    * sci-fi
   * adventure
    * animation
    * action
    * fantasy  

  
* Films in certain languages are more profitable, therefore, production (especially for foreign markets) should focus on movies in those languages. It should be noted that foreign earnings of a movie by language is certainly influenced by the region in which a movie is released & should be taken into account when determining the release language of a given film.  
The top earning languages are (in descending order):
    * Dutch
    * Persian
    * Hindi
    * Mandarin Chinese
    
    
* Films with an older producer tend to earn more as long as the producer is less than seventy years old. Movie producers who are in their sixties should be hired.
    
It should be noted that this analysis only examined what movies grossed the most money, but did not take into account that certain movies may have higher costs (e.g. production, marketing), thus reducing actual profit. Further analysis should include that information to determine which movies are truly the most profitable.
*** 

## For More Information

Please review the full analysis in [the Jupyter Notebook](Movie%20Earnings%20Analysis%20Notebook.ipynb) or the [presentation](Movie%20Earnings%20Analysis%20Presentation.pdf).

For any additional questions, please contact **Elimelech Berlin, melech.berlin@gmail.com**

## Repository Structure


```
├── README.md                                 <- The top-level README for reviewers of this project
├── Movie Earnings Analysis Notebook.ipynb    <- Narrative documentation of analysis in Jupyter notebook
├── Movie Earnings Analysis Presentation.pdf  <- PDF version of project presentation
├── zippedData                                <- Both sourced externally and generated from code
└── images                                    <- Both sourced externally and generated from code
```
