Movie Recommendation System
==============================

This repository contains the code for our project **Movie Recommendation System**, developed during our [Data Scientist training](https://datascientest.com/en/data-scientist-course) at [DataScientest](https://datascientest.com/).

The goal of this project is to create a recommendation system based on the MovieLens 25M dataset using collaborative filtering and model optimization through Deep Learning algorithms.

This project was developed by the following team :

- Lena Ametsbichler ([GitHub](https://github.com/) / [LinkedIn](https://www.linkedin.com/in/lena-ametsbichler/))
- Leonhard Löffler ([GitHub](https://github.com/) / [LinkedIn](www.linkedin.com/in/leonhard-loeffler))

------------
To run the code you need to download the data from [MovieLens](https://files.grouplens.org/datasets/movielens/ml-25m.zip) and extract/save it to the directory data/raw:

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data               <- Should be in your computer but not on Github (only in .gitignore)
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks.


You will need to install the dependencies (in a dedicated environment) :

```
pip install -r requirements.txt
```
--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
