# Under-valued Housing Price

### A description of the problem and a discussion of the background

#### Background & Intent

The intent of this project is to identify areas with undervalued housing price in the United States.
The relevant terms are explained as follows:

- The `area` here is analyzed on ZIP Code level.

    According to [wikipedia](https://en.wikipedia.org/wiki/ZIP_Code#Postal_bar_code),

    > a ZIP Code is a postal code used by the United States Postal Service (USPS).
    As of October 2019, there are 41,702 ZIP Codes in the United States.
    ZIP Codes are used not only for tracking of mail, but also in gathering geographical statistics in the United States.

- This analysis used Zillow Home Value Index (ZHVI) to represent actual `housing price` of a given month in a ZIP Code area.

    According to [Zillow website](https://www.zillow.com/research/data/),

    > Zillow Home Value Index (ZHVI): A smoothed, seasonally adjusted measure of the typical home value and market changes across a given region and housing type.
    It reflects the typical value for homes in the 35th to 65th percentile range.

    > For example, if ZHVI was $400,000 in Seattle one month, that indicates that 50 percent of homes in the area are worth more than $400,000 and 50 percent are worth less (adjusting for seasonal fluctuations– e.g. prices tend to be low in December).

-  This analysis compares the venues (and maybe some other geographical statistics) of a ZIP Code area with the current housing price of that area.
A machine learning model would be built given the housing price and the geographical distribution of venues in that area.
Then, the fitted model will predict the house price based on the venues.
An area would be identified as `undervalued` if the actual housing price is much lower than the housing price predicted from the venues in this area.



### A description of the data and how it will be used to solve the problem

#### Data Source 1:

#### Data Source 2:








-----


1. A link to your Notebook on your Github repository, showing your code. (15 marks)


2. A full report consisting of all of the following components (15 marks):

Introduction where you discuss the business problem and who would be interested in this project.
Data where you describe the data that will be used to solve the problem and the source of the data.
Methodology section which represents the main component of the report where you discuss and describe any exploratory data analysis that you did, any inferential statistical testing that you performed, if any, and what machine learnings were used and why.
Results section where you discuss the results.
Discussion section where you discuss any observations you noted and any recommendations you can make based on the results.
Conclusion section where you conclude the report.


3. Your choice of a presentation or blogpost. (10 marks)
