This project involves web scraping using Python with BeautifulSoup library to extract data, converting the data to csv files and then importing the data in sql server for performing data analysis.
The first table is from the wikipedia page 'https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population' which includes the world population countrywise and their percentage.
The second set of data is from wikipedia 'https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)#Table' which includes forecast of GDP of the year 2023 along with estimate of Gdp from 2022 and 2021 as well.
Note: These are forecasted values and may differ from the actual GDP of the repsective countries.
The analysis performed in sql server are as follows:
a. Data of top 5 economies of 2023
b. Top 5 countries with percentage increase in Gdp from their respective regions.
c. Query to order population wise gdp of countries i.e. countries are arranged in population wise and what is their respective gdp in the world.
d. Query which divides population into large, medium and small and then lists the gdp accordingly (whether small, medium, large).
e. Query giving the per capita gdp for 2023 
