# Statistical-Comparison-of-Socioeconomic-Status-of-Michigan-and-its-neighboring-States
A Statistical comparison of Socioeconomic Status of Michigan &amp; its neighboring States using data scraped from Wikipedia, analyzed and visualized using Python matplotlib &amp; seaborn


Region and Domain category the data sets are about.

Michigan & its neighboring states:
Michigan, Wisconsin, Illinois, Indiana, Ohio, New York, Pennsylvania, West Virginia, Kentucky, Missouri, Iowa, Minnesota

Socioeconomic Status: Variables Considered: Education, Per Capita Income, Unemployment Rate & # Imprisoned ( Crime Indicator)

Research Question
	How does the socioeconomic status of Michigan compare with its neighboring states?


Links


•	https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income
•	https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_incarceration_and_correctional_supervision_rate
•	https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_educational_attainment
•	https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_unemployment_rate 

Image: Refer to the attachments in the Repository

Inference:

The visualization was concerned with answering the question of how the Socioeconomic status of Michigan compares to its neighboring states (Wisconsin, Illinois, Indiana, Ohio, New York, Pennsylvania, West Virginia, Kentucky, Missouri, Iowa, Minnesota) and the comparison is made for the socioeconomic variables like (Education, Per Capita Income, Unemployment Rate & # Imprisoned ( Crime Indicator) ).
Wikipedia was scraped for data concerning each socioeconomic variable for each of the State. All the data points which are used are the updated data from Wikipedia from American Community Surveys, UN Department of Justice, U.S. Census and Bureau of Labor Statistics. Most data which is scraped from Wikipedia is from the 2010 – 2014 American Community Survey, year end 2016 (# Imprisonment) and April 2020 (Unemployment Rate). To have the Y-axis even for all the variables, each of them have been normalized (I have used Min-Max Normalization method) on a Scale of 0 to 1.

The plot indicates high Highschool Graduation Rate for Minnesota, Iowa, and Wisconsin whereas lowest for Kentucky, West Virginia, and New York. The Per Capita income shows less variation than any other socioeconomic variable hovering around 0.5, with its lowest around 0.4 for West Virginia and highest around 0.7 for Minnesota. Unemployment is the only socioeconomic variable which shows the highest variation, with Michigan having the highest unemployment close to 0.8 where as Minnesota having the lowest around 0.2. One interesting observation here is, Michigan, despite having a very good High school Graduation Rate, has the highest unemployment rate as well. All states have almost less numbers of imprisonment with the mean around 0.2. Pennsylvania having the highest # imprisonment close to 0.4 and West Virginia having the lowest # imprisonment around 0.02.
