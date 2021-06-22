# Major League Soccer (MLS) Earnigns (2007-2017)
### Overview
  In this repository you will find one of my first projects, that includes the analysis of Major League Soccer teams from 2007 through 2017. There are three main research questions that were proposed. Those qustions were:
  
- Which  position generated the highest salary over time in the MLS (2007-2017)?
- Which player in the MLS earned the highest salary (2007-2017)?
- Comparatively as a whole, are MLS teams earinng the same total salaries over the years or are there some noticable trends (2007-2017)?

Most of the data sets for each year had missing data, so in order to make the data easier to work with the rows with missing data were disregarded. In order to have those certain rows deleted, the .dropna() function was applied to all of the data sets. Once the rows that had at least one missing value were removed from the data we removed one out of the six columns of the datasets. In order to drop the column, the .drop() function was used. The columns that came with the original dataset were:

- 'club'
- 'last_name'
- 'position'
- 'base_salary'
- 'guaranteed_copensation'

The column that was removed was the 'base_salary'. The reason why the 'base_salary' was removed was because looking what each player was payed overall is what was decided to use for these research questions. 

Each research question contain their own vizualizations in order to help the reader understand what is trying to be told. The main types of vizualizations that were used for the three research questions were bar graphs and scatter plots.

Here is a link to a [StoryBoard](https://lucid.app/lucidchart/d0e37cbe-9081-40e6-983e-96ddb59efef6/edit?viewport_loc=-96%2C-138%2C1280%2C1389%2C0_0&invitationId=inv_48de5a6d-901d-49f5-ae51-64c5f03a39f6) created for this project to get a glimpse of the overall work.

## Tools and Resources
For this project the main workspace was in Google Colab. Tools such as:

- pandas
- numpy 
- matplotlib

were inported in order to be able to work with these datasets.
