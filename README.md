# matplot-challenge

## Background
In this assignment, I looked at data from a study where 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Repo Contains

A folder called Pymaceuticals

Inside of the folder, following are added:
A new file called pymaceuticals_starter.ipynb. This is the jupyter notebook to run the analysis. The jupyter note book also mentions the observable trends based on the data.
A "data" folder that contains the CSV files I used.

## Instructions Followed

The final report includes each of the following:

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* A bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

* A pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* A box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* A mouse was selected that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.
