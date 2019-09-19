# Toronto-Neighborhood-Visualization-for-Potential-Movers
Visualization of Toronto Neighborhoods based on venue type, age demographic, income groups, household size, and unit size. 

This project is prepared as a submission for the final project of the Applied Data Science specialization offered by Coursera ([more information on the program here](https://www.coursera.org/specializations/applied-data-science)). 

The final report can be found [here](https://github.com/Patrickdg/Toronto-Neighborhood-Visualization-for-Potential-Movers/blob/master/Toronto%20Neighborhood%20Visualizations%20for%20Potential%20Movers%20-%20Applied%20DS%20Capstone%20Report.pdf), and the final presentation can be found [here](https://github.com/Patrickdg/Toronto-Neighborhood-Visualization-for-Potential-Movers/blob/master/Toronto%20Neighborhood%20Analysis%20Presentation.pdf).

In addition, the final visualization tools can be found [here](https://nbviewer.jupyter.org/github/Patrickdg/Toronto-Neighborhood-Visualization-for-Potential-Movers/blob/master/Neighborhood%20Visualization%20Maps.ipynb) with a separate version containing all source analysis code [here](https://nbviewer.jupyter.org/github/Patrickdg/Toronto-Neighborhood-Visualization-for-Potential-Movers/blob/master/Neighborhood%20Visualizations%20-%20Toronto%2C%20Canada.ipynb).  

## Problem Statement
For potential movers to new cities, the task of conducting research on the characteristics of neighborhoods can be time-consuming and difficult. However, this task is critical to long-term satisfaction in a new resident's place of stay, especially in a diverse city like Toronto, Ontario where neighborhoods can differ wildly and appeal to very different demographics. In addition, the difficulty of conducting such research is only added on to the overall stress and workload of planning the move, its logistics, as well as the emotional aspect of leaving your old city and life behind. 

Therefore, this analysis will provide a high-level visualization of Toronto's neighborhoods based on several factors which are typical factors under consideration when moving to a new city. More specifically, this visualize will map Toronto's neighborhoods based on the following dimensions: 
- age demographics,  
- income ranges,  
- household sizes (i.e., # of people living in units), and  
- unit sizes (in this case, represented by the # of bedrooms in a unit)  

The target audience for these tools will primarily be individuals actively planning a move and searching for an apartment and/or job in Toronto, Ontario, but can also extend to an indirect target audience of individuals contemplating a move, but unsure of whether their personality/interests would align with what Toronto has to offer. 

## Data Sources
To create these visualizations, the Foursquare API will be scraped to characterize each neighbourhood in Toronto based on venue-types nearby (i.e., near the defined 'center' of each neighborhood, plotted by postal code). This data will be combined with a k-means clustering analysis to cluster the neighborhoods based on similarities of venue types, creating a 'character' map to show potential movers the types of venues that he/she may be interested in having in their new neighborhood. 

In addition, data from the City of Toronto will be used to combine choropleth maps with the 'character' mappings created from the Foursquare API data. Several of these choropleth + character maps will be created to visualize the different consideration factors for potential movers (i.e., age demographics, income, etc.).
