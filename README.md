# Home_Sales
This project is using knowledge of SparkSQL to determine key metrics about home sales data.
#### STEPS
1. Installing libraries and plugins in google collab
2. Creating a SparkSession
3. Reading in the AWS S3 bucket into a dataframe
4. Creating a temporary view of the DataFrame
5. Using filter, agg and average function, i am calculating the desired question
6. writing sql querries and analysing and calculating desired questions
7. creating cache file and running the same querry to test optimization of the querry
8. creating partitioned and parquet file to run same querry for analysing the optimal solution

##### RESULTS

By creating Cache file, the amount taken to run querry got decreased moreover the optimisation increased by doing partition of a data using a parquet file
