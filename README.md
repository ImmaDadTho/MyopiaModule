# MyopiaModule

In this activity I use unsupervised learning to find out if I can group patients into clusters to be able to analyze them separately for myopia.
I use different clustering algorithms to explore wether the patients can be placed into clusters. I also create some visualizations to better 
visualize the outcome. There are four parts to this research ` Part 1 ` Prepare the Data, `Part 2 ` Apply Dimensionality Reduction, `Part 3` 
Perform a Cluster Analysis with K-means, `part 4` MY Recommendation.


## Part 1 - Prepared the Data

- I started with reading in the Myopia.csv file and converted the csv into a dataframe.
- I removed the column I felt were unneccessary, to do this I had to know what the meaning for each column was. I searched online and was 
    able to locate a pdf with the meanings of each column in the MYOPIA dataset and was able to determine what to remove then.
- I standardized the dataset so each column that conatined larger values did not overly influence the outcome.

## Part 2 - Applied Dimensionality Reduction

- I performed dimensionality reduction with PCA and the columns went from 13 to 10.
- I then reduced the dataset further using t-SNE 
- I created a scatter plot and checked for any distinct clusters, I was able to see 3 

## Part 3 - Performed a Cluster Analysis with K-means
- Created an elbow plot to identify the best number of clustering 
- Used a for loop to determine the inertia for each k between 1 - 10 
- Determined that the elbow appears at k-3

## Part 4 - My Recommendation
- With my findings I was able to conclude that we can cluster the patients into three groups. This would be the most effective way to cluster the patients    and recieve the most conclusive data in classifying them.
