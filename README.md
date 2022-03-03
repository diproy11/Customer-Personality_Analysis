# Customer-Personality_Analysis

The job was to segment the customers acording to thier details.

# Step I

I have read the description of the dataset properly and understood the requirement.

# Step II

Imported important libraries.

# Step III

Performing EDA and analyzing dataset by ploting them.

# Step IV

Doing feature aggregation by adding deleting columns.

# Step V

Ploting correlation with the new dataset after feature aggregation.

# Step VI

Created A function for removing outliers but it is not required.

# Step VII

Treansforming Object data type to Integer, and using label encoder to transform String values into numbers.

# Step VIII

Normalizing Data by using MinMaxScaler

# Step IX

Using PCA (Principal Component Analysis) to reduce the dimentionality(Feature/Columns). Used Number of feature 3.

# Now its time to clustering
# Step X 

Frist Using DBscan with epsilon 0.70 and minimun sample size 4 , And got silhouette_score as 60.291320631862334. Then ploted it.

# Step XI

Now trying to KMeans:

Applied Elbow method to find the best number of cluster, and got the cluster number 4.
with 4 cluster I have fitted the dataset into Kmeans and successfully segmented the customers and ploted them.

