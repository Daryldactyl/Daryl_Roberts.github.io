---
title: "Exoplanet Identification Using Clustering / Locating Transit Exoplanets using Lightcurve Data"
excerpt: "This project explores the classification of exoplanets based on features like radius, mass, and orbital characteristics using data from various NASA missions"
collection: datascience
---
## Check out the project [here](https://github.com/Daryldactyl/Exoplanet_Classification/blob/main/planet_clustering.ipynb)
  - I pulled this data from the [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/index.html) and had to do extensive cleaning, parsing, and merging of various tables to generate the dataset. See how I created the dataset [here](https://github.com/Daryldactyl/Exoplanet_Classification/blob/main/data_processing.ipynb)
  - As a BONUS, I also used lightcurve data in order to find exoplanets in transit. Here is the [link to that notebook](https://github.com/Daryldactyl/Exoplanet_Classification/blob/main/exoplanet_finder.ipynb)
## Tools Used
*Data Cleaning, Data Transformation, Merging DataFrames, Feature Selection, Exploratory Data Analysis, Statistics, K-Means Clustering, Unsupervised Learning, Data Wrangling, Regular Expression, Skillful use of Pandas, Attention to Detail, Problem-Solving, Project Management, Dimensionality Reduction, Clustering Evaluation, Sihouette Analysis, Elbow Method, Optimizing Clusters, Data Exploration, Scikit-learn, Plotly, Interactive Graphing, Feature Engineering, Data Interpretation, Communication, Presenting Data Findings*
## Summary:
- **Data Acquisition and Preprocessing:**
Accessed relevant data from the Exoplanet Archive and converted to CSV. Loaded data from a CSV file containing exoplanet features and performed cleaning and transformation steps (handling missing values, converting strings to numerics, renaming columns) to prepare the data for analysis.

- **Feature Engineering and Exploration:**
Calculated summary statistics and created new features (e.g., relative density) to explore relationships between existing features and gain deeper insights into exoplanet properties.

- **Unsupervised Machine Learning and Dimensionality Reduction:**
Employed K-Means clustering to group exoplanets based on their similarities, and Principal Component Analysis (PCA) to reduce the number of features for visualization purposes.

- **Clustering Evaluation and Visualization:**
Utilized Silhouette analysis and Elbow method to determine the optimal number of clusters, and created interactive scatter plots using Plotly.express to visualize the distribution of exoplanets within the identified clusters.

- **Data Interpretation and Analysis:**
Analyzed the characteristics of each cluster (means of features like radius, mass, and orbital period) to draw conclusions about the potential types of exoplanets within each group, suggesting the existence of different exoplanet types like Hot Jupiters, Super-Earths, and Dense Gas Giants based on their characteristics within the clusters.
