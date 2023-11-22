Pymaceuticals Study Overview

This investigation involved 249 mice identified with SCC tumors, subject to diverse drug regimens. Over a 45-day period, meticulous observation and measurement of tumor development were conducted. The central aim of the study was to scrutinize the efficacy of Pymaceuticals' focal drug, Capomulin, in comparison to other treatment regimens.

Task Breakdown:

1. Data Preparation

Execute provided package dependencies and import data.
Merge mouse_metadata and study_results into a unified DataFrame.
Display the count of unique mouse IDs.
Identify and address any instances of duplicate mouse IDs with corresponding time points.
Create a cleaned DataFrame excluding data associated with duplicate time points.
Showcase the updated count of unique mouse IDs.
2. Generate Summary Statistics

Create a DataFrame encapsulating summary statistics.
Include a row for each drug regimen with regimen names as the index.
Incorporate columns for mean, median, variance, standard deviation, and SEM of tumor volume.
3. Create Bar Charts and Pie Charts

Generate two identical bar charts displaying the total number of rows (Mouse ID/Timepoints) for each drug regimen.
Utilize both Pandas' DataFrame.plot() method and Matplotlib's pyplot methods.
Develop two identical pie charts exhibiting the distribution of female versus male mice.
Create the first pie chart with Pandas' DataFrame.plot() method.
Construct the second pie chart with Matplotlib's pyplot methods.
4. Quartiles, Outliers, and Box Plot

Calculate the final tumor volume for mice under Capomulin, Ramicane, Infubinol, and Ceftamin.
Determine quartiles, IQR, and identify potential outliers across these four treatment regimens.
Create a grouped DataFrame showing the last time point for each mouse and merge it with the original cleaned DataFrame.
Formulate a list for treatment names and an empty list to hold tumor volume data.
Iterate through each drug in the treatment list, locating corresponding rows in the merged DataFrame, and append final tumor volumes.
Identify outliers using upper and lower bounds, then print the results.
Employ Matplotlib to produce a box plot illustrating the distribution of final tumor volume, highlighting any potential outliers.
5. Line Plot and Scatter Plot

Select a single mouse treated with Capomulin and generate a line plot depicting tumor volume versus time point.
Develop a scatter plot portraying mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen.
6. Correlation and Regression

Calculate the correlation coefficient and devise a linear regression model between mouse weight and average observed tumor volume during the entire Capomulin treatment regimen.
Overlay the linear regression model on the previous scatter plot.
Following these comprehensive steps will lead to a thorough exploration and understanding of the study's outcomes. matplotlib
