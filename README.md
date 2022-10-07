# TMDb-Movie-Data
This project dives into a dataset provided by The Movie Database (TMDb) on thousands of different movies. 
The various properties associated with movies are visualized using multiple different plots to identify patterns in the data
and answer the key question.

## Key Questions

_1.What kinds of properties are associated with movies that have high revenues?_

_2.Which genres are most popular from year to year?._

## Data Wrangling & Cleaning

The dataset is loaded into a dataframe from the file called *tmdb-movies.csv*. The data is inspected and cleaned for analysis. Duplicate rows and irrelevant columns are removed, variables are renamed, and null values are dropped. 

## Conclusions

Conclusions Based on all of the discovery above, some conclusions are drawn:

**The revenue changed drastically over the year but showed an overall increase. The 1960s accounts for the least, while the 2010s accounts for the most.

**The revenue of high revenue movie shows a strong positive correlation with budget and popularity, and a weak correlation with average voting.

**The most popular genre of the movie changed over the year, although it shows the stability in some periods. Over the year, animation, fantasy, and adventure account for a large proportion of the most popular genre.

**The limitation of this research is that there are so many data that have been cleaned in this report. These datas are seen as anomalies since they contains NaN, duplicates, or 0 in some or all columns. The amount of data changed from 10866 to 3854. The change is huge so that the results may not represent the population.

## Tools

* tmdb-movies.csv
* Python
* Jupyter notebook
