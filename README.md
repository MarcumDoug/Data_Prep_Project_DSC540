## Term Project for DSC 540

After multiple attempts to find this much data about Indianapolis, then Chicago, then just about every other major city in the United States, I decided to venture outside of our boarders to our neighbors up North. There, in the open data sources of Canada, I discovered what I had been searching for this entire time. Posted below are links to the three data sets I will be using for the term project, a description of each, the relationship between each, and what will need to be accomplished to complete the five milestones. 

## Data - Sources and Descriptions   
**Toronto Neighborhood Profiles – CSV File**    
https://open.toronto.ca/dataset/neighbourhood-profiles/  
 
The Census of Population is held across Canada every 5 years and collects data about age and sex, families and households, language, immigration and internal migration, ethnocultural diversity, Aboriginal peoples, housing, education, income, and labor. City of Toronto Neighborhood Profiles use this Census data to provide a portrait of the demographic, social and economic characteristics of the people and households in each City of Toronto neighborhood. The profiles present selected highlights from the data, but these accompanying data files provide the full data set assembled for each neighborhood. Each data point in this file is presented for the City's 140 neighborhoods, as well as for the City of Toronto as a whole. The data is sourced from a number of Census tables released by Statistics Canada. The general Census Profile is the main source table for this data, but other Census tables have also been used to provide additional information. Additional information can be found here: https://www.toronto.ca/city-government/data-research-maps/neighbourhoods-communities/neighbourhood-profiles/  

**Neighborhood Crime Rate (Boundary File) – API**   
https://data.torontopolice.on.ca/datasets/af500b5abb7240399853b35a2362d0c0_0?geometry=-80.685%2C43.542%2C-78.072%2C43.890  
 
Toronto Neighborhoods Boundary File includes 2014-2018 Crime Data by Neighborhood. Counts are available for Assault, Auto Theft, Break and Enter, Robbery, Theft Over and Homicide. Data also includes four-year averages and crime rates per 100,000 people by neighborhood based on 2016 Census Population.  

**Narcity News Article on Toronto Crime Rates – Website for scraping via BeautifulSoup**    
https://www.narcity.com/ca/on/toronto/news/toronto-neighbourhoods-ranked-by-how-dangerous-they-are-right-now-based-on-2018-crime-rates  
This article provides a breakdown of the most common crime occurrence in each neighborhood, as well as the police district the neighborhood resides. This was one of the few sources providing the neighborhoods tied to their districts.  

With these three datasets, there are 140 variables (each neighborhood) and approximately 2400 rows across them.  

## Relationships  
The common relationship running through all three data sets is the neighborhood id (name). This one to many relationship occurs on with each. With this common relationship, there is belief that patterns will emerge across each neighborhood pertaining to crime and different demographics.   

## Steps to Accomplish Five Milestones   
In order to accomplish all five milestones, the data is going to need to be scrubbed and analyzed. The formatting does not align between the three sources, so attention will need to be made in an effort to not cause spurious relationships. Additionally, from a quick review of the neighborhood naming across the three, there appears to be a very slight inconsistency in the naming of each. While only less than five, this connection is vital and will certainly need to be resolved. Looking ahead to the fifth milestone, the visualization of this data is something I am looking forward to a great deal. The mix of statistics and geography should allow for several striking charts and plots. Overall, the project is going to take a great deal of continued focus and new skills to be completed. 
