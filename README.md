# Major League Soccer (MLS) Earnings (2007-2017)
### Overview
  In this repository you will find one of my first projects, that includes the analysis of Major League Soccer teams from 2007 through 2017. There are three main research questions that were proposed. Those qustions were:
  
- Which year and position generated the highest salary over time in the MLS (2007-2017)?
- Which player and in what year earned the highest salary (2007-2017)?
- Comparatively as a whole, are MLS teams earinng the same total salaries over the years or are there some noticable trends (2007-2017)?

Most of the data sets for each year had missing data, so in order to make the data easier to work with the rows with missing data were disregarded. In order to have those certain rows deleted, the .dropna() function was applied to all of the data sets. The columns that came with the original dataset were:

- 'club'
- 'last_name'
- 'position'
- 'base_salary'
- 'guaranteed_copensation'

For all of the research questions only three columns out of the original six were used which include: ‘club’, ‘position’, and ‘guarenteed_compensation’.

Each research question contains their own vizualizations in order to help the reader understand what is trying to be told. The main types of vizualizations that were used for the three research questions were bar graphs and scatter plots.

Here is a link to a [StoryBoard](https://drive.google.com/file/d/1S6sjP8Nu459qbW2ExLQuDu7OG1KAopt5/view?usp=sharing) created for this project to get a glimpse of the overall work.

## Tools and Resources
For this project the main workspace was in Google Colab. Tools such as:

- pandas
- numpy 
- matplotlib

were inported in order to be able to work with these datasets.

Other Links for this project:

- [Poster](https://drive.google.com/file/d/1tH7cfsaGsd22xrMe5jVZEUMZWwBQBEfJ/view?usp=sharing)
- [Slideshow](https://docs.google.com/presentation/d/1XNUmTizNbFcnU3NeSgepd9K3nBNxpSweaSpiI6nDbq0/edit?usp=sharing)
- [Video](https://drive.google.com/file/d/1NDWw537bbtTejovh-zA1zLbBqyBkLD_K/view?usp=sharing)
