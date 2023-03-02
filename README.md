# Tabular Data Science - Final Project - Kernel-Density-Estimation
Project for tabular data science course.
By Liel Gutman and Yaniv Rotics.

## About the Project
The project aimed to improve the selection of hyperparameters in Kernel Density Estimation, specifically the bandwidth and kernel function. The proposed solution involved generating synthetic data from known distributions and evaluating the performance of the KDE model using different bandwidths and kernel functions. The performance was evaluated using mean squared error and total log-likelihood metrics. The "scott" and "silverman" rules-of-thumb were also used for bandwidth selection, and AutoML with grid search and cross-validation was implemented to automate the process of finding the best hyperparameters. The performance of the best methods was tested on four different datasets with unknown distributions. The project's goal was to develop a systematic approach to selecting the optimal hyperparameters for KDE that is applicable to a wide range of datasets and underlying distributions.

The final report can be found [here](https://github.com/lielgut/Kernel-Density-Estimation/blob/main/report.pdf).

## Datasets We Used
1. Avocado prices ([kaggle](https://www.kaggle.com/datasets/neuromusic/avocado-prices))
2. Spotify Songs ([kaggle](https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify))
3. Action movie ratings imdb ([kaggle](https://www.kaggle.com/datasets/rajugc/imdb-movies-dataset-based-on-genre))
4. NASA - Nearest Earth Objects ([kaggle](https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects?select=neo.csv))

To run the project, please use the Python requirement file.

