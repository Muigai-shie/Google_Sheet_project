# Google_Sheet_project
This Project was part of a study project while doing my Data Analytics course.
This Project covers Preparing Data, Cleaning Data, Transforming Data(calculated values, functions), Analyzing data, Creating visualizations and gaiing insights from Raw data.
## Data Importation and Cleaning
*	Imported CSV file to the google sheets.
*	Fixed wrongly imported cells with a different separator, using the split text to columns.
* Validated data to be correctly imported by counting the rows for each column entry(no empty cells eventually)
##  Analyzed the population sizes.
⦁	Created a new column(pop_u_val) to calculate the value of the urban population from the percentage of pop_u and the Nat_pop(in thousands). Function =(pop_u/100)*pop_n
⦁	Created a new column to record the rural pop. Function=pop_n-pop_u_val
⦁	Calculated the %difference in the calculated pop and estimated pop using functions.
## Investigating pop_size by visualization
⦁	By Comparing the national population to the rural and urban share in percentage, the dataset contains some outliers(some population sizes are extremely high)
* Fixed outliers by converting the values to a more comprehensible visualization.
* Created a line chart that compared the population share to the national population.
* Used functions to create the population differences (estimated population and dataset population), and percentage difference in the population shares.
## Investigated and Analyzed the Water access levels compared to the population distribution(rural&urban)
* Created Visualizations to compare the water Access levels in the different population classes and sizes.
## Investigating Water Access by area.
* Calculated Central Tendecies measures to analyze the spread of population across the water distribution levels.
* Created a visualization: Box Whisker Plot(compared the water access levels across population sizes)
## Investigating Water Access 2020 and Income Group
* Used a Pivot table and created visualizations to compare aggregated access levels across populations and income groups.
