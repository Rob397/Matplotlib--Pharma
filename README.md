# Matplotlib--Pharma
Matplotlib Homework
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumour growth were treated through a variety of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results. nstructions.

Your tasks are to do the following: Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID. Use the cleaned data for the remaining steps. Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumour volume for each drug regimen. Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of total mice for each treatment regimen throughout the course of the study.

NOTE: These plots should look identical.

Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study. NOTE: These plots should look identical.

Calculate the final tumour volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

Using Matplotlib, generate a box and whisker plot of the final tumour volume for all four treatment regimens and highlight any potential outliers in the plot by changing their colour and style. Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.

Select a mouse that was treated with Capomulin and generate a line plot of tumour volume vs. time point for that mouse. Generate a scatter plot of mouse weight versus average tumour volume for the Capomulin treatment regimen.

Calculate the correlation coefficient and linear regression model between mouse weight and average tumour volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Here are some final considerations: You must use proper labelling of your plots, to include properties such as: plot titles, axis labels, legend labels, x-axis and y-axis limits, etc. See the starter workbook for help on what modules to import and expected format of the notebook.
