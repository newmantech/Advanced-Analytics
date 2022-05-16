# WHO Air Quality Project

Data Source

I chose the World Health Organization air quality database because I’m interested in comparing air quality across countries and regions of the world, as well as the impact on human health. This dataset has around 32,000 rows and three continuous variables, which include average concentrations in various cities of three types of particulate matter. The dataset also has three categorical variables, including region, country, and city.  It will also come in handy for the time series portion of the project because it includes measurements for the last 20 years. Here is the official description from the WHO website:

“The WHO air quality database compiles data on ground measurements of annual mean concentrations of nitrogen dioxide (NO2), particulate matter of a diameter equal or smaller than 10 μm (PM10) or equal or smaller than 2.5 μm (PM2.5) which aim at representing an average for the city or town as a whole, rather than for individual stations. Both groups of pollutants originate mainly from human activities related to fossil fuel combustion.
The database was released in April 2022 and currently hosts data on air quality for over 6000 human settlements in more than 100 countries.
The database is updated regularly every 2-3 years since 2011 and this is the fifth update. The data compiled in this database is used as input to derive the Sustainable Development Goal Indicator 11.6.2, Air quality in cities, for which WHO is custodial agency.” 

 
Limitations and ethics

There are a lot of missing data. For example, I checked the percentage of missing values in the PM2.5 column, and 14 countries had 95% of data missing for that column (see Jupyter Notebook). According to WHO, “a cutoff of 50% temporal coverage was chosen, with exception for low- and middle-income countries with limited data availability.” This means that some low- and middle-income countries will probably be underrepresented in the data, which raises ethical concerns about sampling and collection bias. The WHO also reports that stations characterized as particular "hot spots" or exclusively industrial areas were not included, unless they were contained in reported city means and could not be dissociated…Omitting them may have lead [sic] to an underestimation of the mean air pollution level of a city.” Another ethical concern arises from the fact that PM and NO2 data are often only available for larger cities, despite the fact that residents of communities of fewer than 100,000 inhabitants and of rural areas “are also exposed to PM and NO2 from local industrial activity, transportation, biomass fuels, open burning and regional haze.” So smaller communities may not get an accurate story of their exposure from these data.
 
Questions to Explore

How do particulate matter concentrations vary by country and city?

Are some types of particulate matter more common in certain parts of the world than others?

How have particulate matter concentrations changed over time?

How do PM concentrations differ by other factors, such as rural vs. urban areas, or the income levels of the communities in which they are measured? 

Which geographic regions, countries, or cities could benefit from more comprehensive measurements of PM? (This could be measured by missing values in the data or low levels of temporal coverage).
