# myopia-clusters
Analyzing myopia data in order to better predict its presence in individuals.

## Summary
A dataset of individuals tested for myopia was analyzed in order to see whether clustering these individuals would be of benefit for future diagnoses. Data was imported
into a notebook and both PCA and TSNE were performed in order to reduced the number of dimensions. 90% of the variance was accounted for by the retained variables and
the remaining dimensions were further compressed into two values per individual. A plot was constructed to visualize these values. Finally, a KMeans was performed in 
order to identify the best suited number of clusters for the data. Another plot was drawn with the specified clusters colored. A recommendation was made suggesting that
clustering in this way may not be the most beneficial in more efficiently predicting myopia in the future.
