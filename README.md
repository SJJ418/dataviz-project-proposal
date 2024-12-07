# Data Visualization Project

## Data

The data I propose to visualize for my project is [[![image](costOfLivingDataset.png)](https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024)

A cost of living index of 100 is equivalent to New York City where monthly costs for a family without rent are $6,074.40 and individuals are $1,640.90.

* Cost of Living Index (Excl. Rent): This index indicates the relative prices of consumer goods like groceries, restaurants, transportation, and utilities. It excludes accommodation expenses such as rent or mortgage. For instance, a city with a Cost of Living Index of 120 is estimated to be 20% more expensive than New York City (excluding rent).
* Rent Index: This index estimates the prices of renting apartments in a city compared to New York City. If the Rent Index is 80, it suggests that the average rental prices in that city are approximately 20% lower than those in New York City.
* Cost of Living Plus Rent Index: This index estimates consumer goods prices, including rent, in comparison to New York City.
* Groceries Index: This index provides an estimation of grocery prices in a city relative to New York City. Numbeo uses item weights from the "Markets" section to calculate this index for each city.
* Restaurants Index: This index compares the prices of meals and drinks in restaurants and bars to those in NYC.
* Local Purchasing Power: This index indicates the relative purchasing power in a given city based on the average net salary. A domestic purchasing power of 40 means that residents with an average salary can afford, on average, 60% less goods and services compared to residents of New York City with an average salary.






## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * I want to understand the geographical distribution of the cost of living index.
 * I want to see correlation between rent index and groceries index.
 * I want to see correlation between local purchasing power index and the cost of living index.
 * I want to see correlation between the cost of living index dataset and the global country development and prosperity index dataset.
 * I want to understand the geographic distibution of rent index.

## Sketches

Below is first sketch of my proposed visualization.

[![image](https://github.com/SJJ418/dataviz-project-proposal/blob/master/salaryVsCostOfLiving.jpg)

Below are iteration comments for my first visualization sketch.

[![image](https://github.com/SJJ418/dataviz-project-proposal/blob/master/salaryVsCostOfLivingIteration.jpg)


## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar chart that shows the top ten countries by cost of living along with a line graph that represents the median salary in each of those top ten countries.

[![image](https://github.com/SJJ418/dataviz-project-proposal/blob/master/costOfLivingIndexTop10.png)](https://vizhub.com/SJJ418/17194ee381f74b17902515e736096d57)

[![image](https://github.com/SJJ418/dataviz-project-proposal/blob/master/medianSalaryTop10.png)](https://vizhub.com/SJJ418/f887f1018b6e41329931308b5ce4c691)


## Open Questions

I am currently looking into additional channels to represent the data within each set. This may include country selection that could include a radar chart that shows cost of living attributes, or a breakdown of the jobs in each country that median salaries are from.

## Milestones

* Week 8   - Implement full datasets
* Week 9   - Combine line and bar chart
* Week 10  - Explore additional ways to represent individual countries
* Week 11  - Implement individual country representation
* Week 12  - Add tooltips
* Week 13  - Finalize visualization
* Week 14  - Write report


## Week 9

Full datasets have been implemented into previous data visualizations. At this point, I may be pivoting to add the ability to show additional data per country, one country at a time, instead of just the top ten cross examined with salary. Each country will be selectable.

[![image](https://github.com/SJJ418/dataviz-project-proposal/blob/master/costOfLivingIndexTop10.png)](https://vizhub.com/SJJ418/cost-of-living-by-country-top-10-rev1?file=index.js&tabs=index.js%7Ecost_of_living_index.csv)

## Week 10

Direction change for vizualization. Data set applied to world map that allows for country selection (currently mouseover only). Next steps are to include additional data per country selected. This information will appear in a popup when a country is clicked. Possible graphics include radar chart of index breakdown, country rankings and salary display. Any advice on additional information to include or methods to compare countries would be appreciated. Thank you!

[![image](costOfLivingIndexWithCountrySelection)](https://vizhub.com/SJJ418/cost-of-living-world-map-with-country-selection?edit=files&file=cost_of_living_index.csv&tabs=map.js%7Eindex.js%7Epackage.json%7Ecost_of_living_index.csv)

## Week 11

Color key added (still working to make color gradient interpolation work with key). Added country selection fucntionality to represent additional country data. Next steps are to fix colors and create additional visualizations for additional country information.


[![image](colorKey)](https://vizhub.com/SJJ418/cost-of-living-world-map-with-country-selection-and-color-scale?mode=embed)


[![image](countryPopUp)](https://vizhub.com/SJJ418/cost-of-living-world-map-with-country-selection-and-color-scale?mode=embed)

## Week 12

Color was changed to use a color scale (currently not interactive) however country pop-up is functional and displays country and cost of living. Next steps are to add secondary vizualization to pop-up that breaks down the cost of living scoreds in each country and displays rank.

[![image](costOfLivingColorScale.png)](https://vizhub.com/SJJ418/cost-of-living-map-with-colorscale-and-country-pop-up?mode=embed)


[![image](countryCostOfLivingPopUp.png)](https://vizhub.com/SJJ418/cost-of-living-map-with-colorscale-and-country-pop-up?mode=embed)

## Week 13

Radar Graph is added when country is selected. Next steps are to clean up presentation and add color gradient to circles in radar chart.

[![image](costOfLivingRadarChart.png)](https://vizhub.com/SJJ418/cost-of-living-map-with-radar-chart-pop-up?mode=embed)

## Week 14


