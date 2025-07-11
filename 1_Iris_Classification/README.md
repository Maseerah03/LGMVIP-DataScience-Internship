# Iris Flowers Classification

This project was completed as part of my Data Science Internship at LetsGrowMore (October 2023 batch). The objective was to apply unsupervised machine learning techniques to classify different species of iris flowers and visualize the results.

## Objective

To perform clustering on the Iris dataset and analyze the natural groupings among the three species: Setosa, Versicolor, and Virginica, using the K-Means algorithm. The project also includes exploratory data analysis and accuracy evaluation.

## Tools and Libraries Used

- Python
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn (KMeans, confusion_matrix)

## Summary of Work

- Loaded the Iris dataset using seaborn’s built-in library.
- Encoded the species labels using `pd.factorize` for easier comparison.
- Performed basic exploratory analysis and checked for missing values.
- Visualized the dataset using both 2D and 3D scatter plots for sepal and petal measurements.
- Applied the Elbow Method to determine the optimal number of clusters.
- Implemented the K-Means clustering algorithm on petal length and width features.
- Evaluated clustering performance by comparing predicted clusters with actual species labels using a confusion matrix.

## Key Outcomes

- Identified three natural clusters in the dataset, aligning well with the known species classifications.
- Generated a confusion matrix to assess the match between predicted clusters and actual species.
- Gained experience in unsupervised learning, data visualization, and cluster evaluation.

## Files Included

- `Iris_Classification.ipynb` – Google Colab notebook containing the full analysis and results.
- `README.md` – Project summary and explanation.

## Acknowledgement

This project was developed during my internship at LetsGrowMore under the guidance of Mr. Aman Kesarwani.
