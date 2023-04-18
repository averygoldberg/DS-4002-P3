# DS-4002-P3
## Project 3 - Knights of Avril
In this github repository you will find our README.md file, LICENSE.md file, SRC, Data, and Figures folders. Our README.md file (the file you are currently reading) will serve as a guide to what is contained in our repository. Our LICENSE.md file explains how visitors can interact with this repository. The SRC folder contains all of our source code for the project. The Data folder contains our dataset. Finally, our Figures folder contains all our graphs we created to explore our hypothesis.

## SRC
### Installing Code
You can download our code from this repository in the SRC folder. 
### Usage
To use our code, simply download the file above and run it in RStudio, ensuring all necessary packages are installed. 

## DATA
| Variable | Type | Description |
| --- | --- | --- |
| country | Character | Country where the happiness score was assessed |
| year | Numeric | Year in which the happiness score was recorded |
| score | Numeric | Happiness score is measured as the national average response to the question of life evaluations asking the following “Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?” Gapminder converted this indicator's scale from 0 to 100 to easily communicate it in terms of percentage [1]|

The score variable was extracted from the original dataset which had country and year variables with the happiness score for each country listed under the given year.


You can download the dataset from:\
[GapMinder: Happiness Score Data](https://www.gapminder.org/data/) by clicking on the "Select an indicator" drop-down menu and searching "Happiness score (WHR)". The dataset can also be downloaded from the DATA folder in this repository.

Our data was used to explore our hypothesis: *50% of countries has a lesser decrease in their happiness score compared to the U.S. during 2006-2021.*

## FIGURES
| Figure | Summary |
| ------ | ------- |
| Linear Regression US Happiness Score Scatter Plot | Scatter plot displaying the linear regression line for the United States Happiness Score over time. |
| Relative Percent Decrease Bar Plot | Bar plot displaying the percent decrease in Happiness Score of various countries relative to the United States, indicating where the score decreased more or less than that of the United States over time. |
| Relative Percent Decrease Pie Chart | Pie chart displaying the portion of countries whose Happiness Score fell into each relative decrease category. This chart proves the hypothesis by showing the percent of countries whose Happiness Score decreased more and less than the United States. |


## REFERENCES
[1] N. Hisham, "WHR-Happiness Score," version 4, GapMinder, Mar. 25, 2023. [Dataset]. Available: https://www.gapminder.org/data/. [Accessed: April 4, 2023].\
[2] hadley, "Linear Regression and group by in R," *Stack Overflow*, Jul. 31, 2009. [Online]. Available: https://stackoverflow.com/questions/1169539/linear-regression-and-group-by-in-r. [Accessed: April 11, 2023].\
[3] "Pie chart with percentages in ggplot2," *R Coder*. [Online]. Available: https://r-charts.com/part-whole/pie-chart-percentages-ggplot2/. [Accessed: April 13, 2023].
