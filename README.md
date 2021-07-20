# CrimeAnalysis

# What does this repo do?
I analysed 2.11 million records for Crime in Los Angeles between 2010-2019 for interesting results. I started by conducting EDA to see what trends were present.

In the end I managed to statistically show that there is differences in the arrest rates for crimes committed against ethnic minorities and towards females. I also showed that certain areas of society are statistically more likely to be the victim of certain crimes.

# Description of files
**Crime Final.ipynb**: Main file that holds all of the analysis.

**Common_Combinations.csv**: Gives pairwise combinations for each Victim Descent and Gender and then counts the number of times they were a victim of each crime. The file is then ordered in descending order.

**CrimeOutcomes.csv**: Gives the count for each outcome for each crime, including: Investigation Continues, Unknown, Arrested, Other. From here we calculate the proportion arrested to see how the crime rate differs depending on crime. This is on a high level and does not tell us anything about who the victims of the crime are.

**Crime_List_Annotated.csv**: Lists all the crimes that occurred with an additional column where I have tried to classify each crime into it's type. I was interested to find out whether, for example, Sexual Crimes increased in prevelance over time compared to say Property Crimes.

# Things I have learnt from this project
I learnt how to create a basis map and a map that changes through time using the Folium package. I need to improve these maps to be able to do robust statistical analysis but for a first attempt I am proud of the overall visual EDA it gives. In future I would like to separate the areas into the 21 distinct boroughs and show the levels of crime on an area level rather than using the latitude and longitude.
