# R-Programming
## Problem Statement
Home Depot/Lowe's Case:

How do these two chains make their decisions about where to have store locations? What are the major criteria that drive this decision, and can you provide a very brief rationalization for each? Essentially, this question gets at how the two chains are similar in their decision making.
Are there ways in which the two chains are different in the types of locations they target? What are those differences, and why do you think that they may be apparent in the data? Characterize the targeting strategies for each of the two chains.
What counties appear under-served in the data, by one or both store chains? Where would you expect Home Depot to open its next 2-3 locations? Lowe’s?

## Solution
1)	How do these two chains make their decisions about where to have store locations? What are the major criteria that drive this decision, and can you provide a very brief rationalization for each? Essentially, this question gets at how the two chains are similar in their decision making.

•	In order to understand the major criteria that drive their decision about where to have store locations, I performed linear regression using R programming.
            Common Factors for Both Stores:
•	Pop_2010: Population indicates number of potential customers. So more the population, more would be the profit for Home Depot Stores
•	Density_2010: Increase in the density represents that more customers stay in nearby locations. However, less density represents the population is spread in different locations and there is need of more stores to serve them.
•	Income_2010: Large income represents more chances of the customers wanting to spend on home Decoration.


•	Lowe’s Store:
 
•	The R-squared value of 64.16% represents that the model is strong and the above factors do have an impact on their decision to determine number of stores in a particular location.





Home Depot stores
 
The R-squared value of 90.51% represents that the model is strong and the above factors do have an impact on their decision to determine number of stores in a particular location.

•	Home Depot stores also consider:
Pctcollege_2010: Increase in the percent of the county’s residents with a college education represents chances of them to earn more and spend on such stores.
 


2)	Are there ways in which the two chains are different in the types of locations they target? What are those differences, and why do you think that they may be apparent in the data? Characterize the targeting strategies for each of the two chains.
 

 


The above graphs represent the distribution of both the stores in United States.
It is clear that population, density and income play an important role while deciding number of stores in different states.
However, there are some additional factors that are considered while making this decision:
1)	Lowe’s Companies was founded in North Carolina, and hence we see many stores in and around the state of NC.
2)	Although, both the stores might have common factors while considering the number of stores in a particular state, However, the proportion by which each factor may affect the decision will be deferent.
3)	For example, the correlation between Lcount and Population is 78.34% and the correlation Between HDcount and Population is 93.95% 
4)	This represents that population has a greater impact on the decision making of Home Depot than in the case of Lowe’s Store.

 

3)	What counties appear underserved in the data, by one or both store chains? Where would you expect Home Depot to open its next 2-3 locations? Lowe’s?

•	Home Depot should open its store at Albany, WY based on following inferences:
























 
Since the density is high, one store would be enough in Albany, WY to serve all the customers.

 

The next Home Depot store should be opened at Pennington, SD as per the following statistics
 

The population is high, with a decent average income, but there is no store to serve these residents. A new store would definitely work out well with Home Depot.

Lowe’s Store:

District of Columbia, DC should be the next place where Lowe’s should consider opening its next store.
 

Lowe’s should also consider opening its store at Anchorage, AK
The population there is high, and the density being low representing the population is spread across different areas.
Hence, in order to serve the entire population, opening a new store would be beneficial for Lowe’s.
 

