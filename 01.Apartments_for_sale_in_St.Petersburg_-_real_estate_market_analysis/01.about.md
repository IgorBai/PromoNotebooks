Open [:open_file_folder:**IPYNB**](01.Apartments_for_sale_in_St.Petersburg_-_real_estate_market_analysis.ipynb) [:open_file_folder:**HTML**](01.Apartments_for_sale_in_St.Petersburg_-_real_estate_market_analysis.html)
### 01. Apartments for sale in St.Petersburg - real estate market analysis.

__Description__
- This is the first full-scale work on research data analysis. It investigates the archive of ads for the sale of apartments in St. Petersburg and neighboring settlements, in the future, the dependencies and indicators found here will be used in the system of checking new ads for validity.

__Tools & experience__
- seaborn
- matplotlib 
- numpy 
- pandas 
- os 
- research data analysis
- data visualization 
- data preprocessing

__Steps__
- Data is read, preprocessed, obvious garbage is filtered out. 
- Duplicates and omissions are checked. Prices are calculated for 1 sq.m., graphs are built (26 pcs in total) linking the number of floors, the duration of the sale, the distance to parks and other objects with the cost of housing. 
- Price variations are investigated during the week and over 6 years of observations. 
- The dependence of the price of 1 square meter on the distance to the city center is calculated.

__Conclusions__
- The study analyzed a dataset of ads for real estate sales in St. Petersburg and the region, submitted in the period from November 2014 to May 2019. The number of analyzed rows is ~ 18000. The range of the cost of objects is from 12 thousand rubles to 763 million rubles, the spread of the total area is from 12 to 900 sq.m, in buildings with a height of 1 to 60 floors, with a number of balconies up to 5, the distance to the nearest ponds and reservoirs is from 13 to 1300 meters. There are objects that were sold in 1 day, but there are also objects that have been on sale for more than 4 years.
- Data preparation, removal of explicit and implicit duplicates, as well as omissions in the data were carried out in the work. Calculation tables are presented, 26 graphs and histograms are studied, to which descriptions and explanations are given. Graphs and calculations are averaged and can serve as a criterion for the anomaly of the submitted ads (i.e., the basis for checking for falsification) if the numbers in the ads differ too much from the average.
- Half as many ads are served on weekends as during the week. Average (not median) prices jump from Friday to Saturday, which means that ads with an increased price are served on Friday.
- It is interesting that with the increase in the number of floors, the average area of the objects sold also grows. That is, with the rise to the top, sales become "more wholesale".
- The decrease in the average price of 1 sq.m. in St. Petersburg at a distance from the center is non-monotonous: in the range of 3-7 km, prices even rise, not fall (the rise in price of 1 sq.m is +8660 rubles/km). The reduction in the cost of 1 sq.m in the range of 8-29km is on average 1320 rubles/km.
- Basically, housing is for sale at a distance of 2-17km from the center. At a distance of about 30 km from the center, the price drops by almost 3.4 times.
- Average price per square meter in St. Petersburg (2nd place, 114680r/sq.m.) is not as high as in Zelenogorsk (1st place) - 115123 rubles per meter. With a price of 84758 rubles per meter Peterhof (10th place) closes the rating of the most expensive settlements of the Leningrad region.
- The real estate market in the Leningrad region sank after 2014, at the end of the period under review there is a tendency to its recovery.



