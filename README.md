# Project description
This project deals with the classification of movies by genre based on posters. The classification model used is a CNN whose base is an overtrained DenseNet169 network to which some additional layers are added. The parameters tested during training are the learning rate and the number of trained layers of the DenseNet169 network. Regularization is performed by adding a Dropout layer. Since the dataset on which the project was built is very unbalanced and the problem is a multilabel classification, the following metrics are used to evaluate the model: F1 score, AUC score, and Brier score.
# Dataset
The dataset used can be found at: *data/movies_initial.csv*. More information about dataset can be found on following link https://www.kaggle.com/datasets/samruddhim/imdb-movies-analysis. The original dataset contains a large number of attributes, of which we will keep only a few:
  - title - name of the movie
  - imdbID - IMDb ID of the given movie
  - genre - a set of at most 3 genres to which the given movie belongs
  - poster - URL to the image of the given movie
# Structure
- folder src - containing the code notebooks
- folder data - containing the original dataset and a Google Drive link containing all other data saved during preprocessing
- folder models - containing the trained models
# Packages
- pandas
- numpy
- matplotlib
- sklearn
- tensorflow
- tabulate
# Literature
- http://cs230.stanford.edu/projects_winter_2020/reports/32643471.pdf

