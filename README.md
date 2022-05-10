## Visualizing Median Income Change in Cities with New Baseball Stadiums

**Authors:** Eugene Lau, CYPLAN 255

### Problem Statement
Map Showing All Baseball Parks in US
![Screenshot 2022-04-27 012612](https://user-images.githubusercontent.com/98058718/167568144-8f65c7d2-9036-4c75-9f85-49c48859514c.jpg)


I am exploring potential relationships between the development of major league baseball stadiums and city level median income data using Census 5 Year ACS data. Broadly I am looking at how the arrival of baseball stadiums produce either negative or positive changes in the financial capacity of surrounding residents. Economists regularly argue that public funding for sports venues does not bring in the economic and social returns expected by taxpayer investment. This history of public investment in sports venues results in little economic benefit to the surrounding area besides to the investors in the project. Professor of Economics Victor Matheson argues that NFL stadiums in particular make poor neighbors as they generate little to no local economic benefit, bringing in residents already in the metro area, and facilities are hardly utilized beyond for the team’s benefits. A recent study suggests $33 billion public dollars in the United States went to covering a median of 73% of total construction costs over the past 30 years. These public dollars could have been tailored for essential city services like education, economic development, transportation, and parks maintenance.  

Map Showing Subject Baseball Parks in US
![Screenshot 2022-05-09 222233](https://user-images.githubusercontent.com/98058718/167548157-453d7c75-072b-4ea7-8196-fd5af85eb694.jpg)

### Goals
My goal is to produce exploratory chloropleth maps for each of these baseball cities to show the changing median income levels in each of these cities. Most economists argue that investments into sports stadia do not produce economic benefits for the surrounding communities. The Census bureau started collecting 5 year ACS data in 2010. In addition the Python library I accessed - CENPY - only provided 5 Year ACS data starting in 2013. To make accurate comparison, I looked at stadiums built between slightly before and during this time span - Nationals Park in DC (2008), Yankee Stadium in NYC (2009), Citi Field in NYC (2009),Target Field in Minneapolis (2010), and Loan Depot Park in Miami (2012). This project is primarily an exercise to explore Python as a tool to access and visualize Census data.

Note that incomplete data will not show up on the maps and the Census reports median income up to a maximum of $250,000/year.


### Washington, DC

#### Median Income 2013
![dc13](https://user-images.githubusercontent.com/98058718/167570431-05eee5ba-8f3c-4d65-b7b7-ed4b50cd8f07.png)


The highest concentration of wealth is located adjacent to the Georgetown neighborhood with wealthier neighborhoods located in Northwest DC.


#### Median Income 2018
![dc18](https://user-images.githubusercontent.com/98058718/167570447-c87bbdb6-cca0-4913-94af-e06c6eb7bfb2.png)


Median incomes rose across the board in DC with a significant portion of the city. The 2013 pattern has spread across the city but the neighborhoods across the Anacostia river are still less income rich. 


Percent Change, Median Income 2013-2018
![dc1318](https://user-images.githubusercontent.com/98058718/167562307-ea06365e-722e-4e16-8369-804a741b54cd.png)

There is a substantial percentage change in the Navy Yard neighborhood where the Nationals Park is located with similar change in median income occuring across the river in the Anacostia neighborhood.



### New York City

Median Income 2013
![ny13](https://user-images.githubusercontent.com/98058718/167562321-03a55e15-a05d-4c9e-941f-cf89b7d9b60a.png)
Most of the income wealth in NYC is located in Manhattan around Central Park and Midtown. 



#### Median Income 2018
![ny18](https://user-images.githubusercontent.com/98058718/167562328-e1417dec-9e7e-44b3-8e41-294ee89869da.png)

A majority of NYC's tracts recieved a bump in median income. 



#### Percent Change, Median Income 2013-2018
![ny1318](https://user-images.githubusercontent.com/98058718/167562341-9e6ec93e-e3d8-4094-bd97-9c2bc0385b69.png)

There appears to be no significant difference between the rise of income where the Yankee Stadium is located in the upper corner of NYC. The Mets stadium is located in Flushing Meadows a public park in the Queens borough so no income data is reported by the Census here. Surrounding neighborhoods don't seem to have recieved an income bumpo either just like Yankee Stadium in the Bronx. 



### Minneapolis

#### Median Income 2013
![mn13](https://user-images.githubusercontent.com/98058718/167570505-7c1e7ad2-6b39-4394-99a9-43f2338d28b8.png)


The majority of wealth is located in the Southern left edge and upper center of Minneapolois with incomes topping out around 120k.



#### Median Income 2018
![mn18](https://user-images.githubusercontent.com/98058718/167570525-d3097910-9153-4b8b-bd08-1aac108e0c22.png)


Wealth increased through Minneaopolis in that 5-year span as top incomes reached beyond $140k.



#### Percent Change, Median Income 2013-2018
![mn1318](https://user-images.githubusercontent.com/98058718/167562395-cde7e8e0-9fa5-470e-b731-09e4d63272ad.png)

The area of the ballpark recieved the least amount of median income change. However adjacent tracts recieved the highest amount of percent change.


### Miami

#### Median Income 2013
![fl13](https://user-images.githubusercontent.com/98058718/167570558-76eae43a-4c03-4d01-b334-17e3d3a6bdec.png)

The majority of wealth in Miami appears to be located on the lower right edge alongside the waterfront. 



#### Median Income 2018
![fl18](https://user-images.githubusercontent.com/98058718/167570573-783c7fb0-f6e1-4245-9286-f659de709706.png)

The 2013 pattern is repeated but the smaller tracts inland tracts around the waterfront are going up in wealth. 



#### Percent Change, Median Income 2013-2018
![fl1318](https://user-images.githubusercontent.com/98058718/167562421-5a645ef6-708c-4e56-ae08-16d152f60803.png)

The tract that the ballpark is located in doesn't appear to have increased that much in median income change but surrounding neighborhoods have. 

### Closing Thoughts

Between 2013 and 2018, it appears that the tract where Nationals Park is located in Washington D.C. recieved the highest degree of change in median income. Though there is a possibility that the development of the park in 2008 was the genesis for such a change, D.C. has also underwent a massive amount of demographic and socio-economic change. Plans to redevelop the Navy Park neighborhood began in early 2000 and is still on-going. These development plans and gentrification in D.C. could be more to explain for the change in median income levels rather than the introduction of the ballpark. 

Yankee Stadium, Citi Field, Target Field, and Loan Depot Park do not share the same percent median income change in their respective neighborhoods. Though each host city recieved a bump to median incomes between 2013-2018 in a majority of their tracts. Further research should look at other variables besides median income to explore how these stadiums impacted these cities on a neighborhood scale and if there is relevance to redevelopment schemes beyond the stadium like there was in D.C. and if public funding played a part in the financing for construction. 
