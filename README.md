# module_5_challenge

Imported the needed modules
Imported the CSV data files
Read the mouse data and the study results CSV files
Combined the data from both CSV files into a single DataFrame on the Mouse ID column.
Displayed the data table from the combined DataFrame for preview
Checked the number of mice.
Got the duplicate mice by ID numbers that shows up for Mouse ID and Timepoint. 
Pulled all of the duplicate values into a separate DataFrame
Created a clean DataFrame by dropping the duplicate mouse by its ID.
Confirmed the new DataFrame was clean by checking the number of mice in the clean DataFrame.
Generated a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen
Used groupby and summary statistical methods to calculate the following properties of each drug regimen: mean, median, variance, standard deviation, and SEM of the tumor volume.
Assembled the resulting series into a single summary DataFrame.
Used a more advanced method to generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen using the groupby()method.
Generated a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using Pandas.
Generated a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen using pyplot.
Generated a pie plot showing the distribution of female versus male mice using Pandas. Grouped by the "Sex" column and counted the number of mice in each category.
Generated a pie plot showing the distribution of female versus male mice using pyplot. Grouped by the "Sex" column and counted the number of mice in each category.
Calculated the final tumor volume of each mouse across four of the treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin
Placed treatments into a list for for loop (and later for plot labels)
Created an empty list to fill with tumor vol data (for plotting)
Calculated the IQR and quantitatively determined if there are any potential outliers.
Located the rows which contain mice on each drug and got the tumor volumes.
Added a subset.
Calculated and printed the IQR for each regimen.
Determined the outliers using upper and lower bounds
Generated a box plot that shows the distrubution of the tumor volume for each treatment group.
Generated a line plot of tumor volume vs. time point for a single mouse treated with Capomulin.
Generated a scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen
Grouped by "Mouse ID" to calculate the average tumor volume for each mouse in the Capomulin regimen.
Calculated the correlation coefficient and a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen.

# Acknowledgements
I received assistance from 5 LA's for this exercise. Ian, Kat, Marissa, Daniel and Ryan.
I also used google bard and chatGPT for help with syntax cleaning and correcting the syntax.
