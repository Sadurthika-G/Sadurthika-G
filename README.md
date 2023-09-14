#EARTHQUAKE ANALYSIS





Data Preprocessing:

ATImport necessary libraries.
Read earthquake data from a CSV file into a Pandas DataFrame.
Convert the 'date' column to a datetime format and extract features like 'month,' 'quarter,' 'year,' 'hours,' 'minutes,' 'dayPeriod,' 'earthquakeCategory,' 'season,' and 'depthCategory' from the date and time columns.
Select specific columns of interest and filter the data for a specific time range (years 2011 to 2020).



Data Visualization:

Visualize the data using various types of plots such as box plots, histograms, and count plots to explore numerical and categorical features.
Create count plots for combinations of categorical features to analyze relationships between them.
Generate count plots for combinations of features and the 'year' variable.



Clustering:

Normalize the 'longitude' and 'latitude' columns using Min-Max scaling.
Perform K-Means clustering on the normalized 'longitude' and 'latitude' features and add the cluster labels as a new column ('area') to the DataFrame.
Visualize the clusters on a scatterplot.



Further Analysis:

Analyze the distribution of categorical features within each cluster.
Encode and normalize categorical features.
Perform K-Means clustering on the encoded categorical features and add the cluster labels as a new column ('cluster1_9') to the DataFrame.
Visualize the clusters on a scatterplot.



Statistical Summary:

Calculate statistics for the 'depth' and 'magnitude' features within each cluster.
Perform K-Means clustering on the normalized 'depth' and 'magnitude' features and add the cluster labels as a new column ('cluster2_3') to the DataFrame.
Visualize the clusters on a scatterplot.



Additional Analysis:

Analyze the distribution of categorical features within each cluster formed based on 'depth' and 'magnitude'.




