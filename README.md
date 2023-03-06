# Tabular Data Science - Final Project - Kernel-Density-Estimation
Project for tabular data science course.
By Liel Gutman and Yaniv Rotics.

## About the Project
The project aims to improve the selection of hyperparameters in Kernel Density Estimation, specifically the bandwidth parameter which impacts the smoothness of the estimation. The proposed solution involves using different bandwidths including "scott" and "silverman" rules-of-thumb, and Grid Search Cross-Validation which is an AutoML method available in Scikit Learn that estimates the best hyperparameters.
The performance was evaluated using mean squared error (MSE) and total log-likelihood metrics. The performance of the best methods was tested on known distributions and four different datasets as well.

The final report can be found [here](https://github.com/lielgut/Kernel-Density-Estimation/blob/main/report.pdf).

## Datasets We Used
1. Avocado prices ([kaggle](https://www.kaggle.com/datasets/neuromusic/avocado-prices))
2. Spotify Songs ([kaggle](https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify))
3. Action movie ratings imdb ([kaggle](https://www.kaggle.com/datasets/rajugc/imdb-movies-dataset-based-on-genre))
4. NASA - Nearest Earth Objects ([kaggle](https://www.kaggle.com/datasets/sameepvani/nasa-nearest-earth-objects?select=neo.csv))

To run the project, please install the requirements and run and jupyter notebook.

