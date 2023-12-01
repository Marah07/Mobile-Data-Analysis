# Mobile-Data-Analysis

This project is structured into two primary components: Trajectory DataFrame and Flow DataFrame analysis, powered by the scikit-mobility library, unfolds as follows:

<strong> Trajectory DataFrame: </strong>

Addressing specific aspects of the check-in data collected in New York City (NYC) and Tokyo over a 10-month period from April 2012 to February 2013. The dataset, sourced from Kaggle, comprises 227,428 check-ins in NYC and 573,703 in Tokyo, including timestamps, GPS coordinates, and semantic meaning in fine-grained venue-categories:

- Reading and exploring the check-in dataset.
- Creating a Trajectory DataFrame (tdf) to represent the spatial-temporal trajectories of users.
- Applying trajectory preprocessing techniques, including noise filtering, stop detection, compression, mobility measures, and privacy protection.
- Developing two algorithms: Markov Diary Learner and Generator, and Density-ERP model.
- The Markov Diary Learner employs a data-driven approach to compute a mobility diary, utilizing a Markov model to describe routine and non-routine behavior.
- The Density-ERP model generates a Flow DataFrame based on spatial tessellation, considering population density as a relevant factor.
 -Visualizing trajectories and mobility patterns using the nyw DataFrame, providing insights into spatial-temporal regularities of user activity.
  
<strong> Flow DataFrame: </strong>
  
- Utilizing the NY_counties_2011.geojson dataset to create a Flow DataFrame (fdf)
- Visualizing trajectories and flow patterns to gain insights into the spatial-temporal regularity of user activity.
- Implementing visualization techniques for both Trajectory and Flow DataFrames, enriching the understanding of mobility patterns in urban environments.
  
The repository includes Jupyter Notebook files for each step of the analysis for both Trajectory and Flow DataFrames, ensuring code reproducibility. Relevant datasets (nyc DataFrame and GeoJSON file) for spatial visualization are also included. This project aims to offer a comprehensive exploration of mobile data analysis techniques, providing nuanced insights into user mobility patterns through visualizations in large-scale urban environments.
