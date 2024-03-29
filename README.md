

The easy pet-project made to practice sklearn, pandas and other ML libraries.
A point of the project is to build a model suitable for prediction of a mean temperature using features given in the dataset about the weather in London.


# Contents
- [Technologies](#Technologies)
- [Analysys](#research)
- [Model](#model)
- [Test](#test)
- [To do](#to-do)
- [Team](#Team)

# Technologies
- [Pandas](https://pandas.pydata.org/)
- [Sklearn](https://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/)
- [LightGBM](https://lightgbm.readthedocs.io/en/stable/)
- [Catboost](https://catboost.ai/)


# Research

The research part of the project includes import and analysis of
features, making new features and fixing nans.

# Model

Mean temperature has been chosen as a target whereas other ones chosen as features. MAE has been selected as the metrics to evaluate models.  

# Test

As a result I made the pipeline with gradient boosting model (LightGBM model) as the model with the smallest MAE

# To do
- [ ] Make own Decision Tree
- [ ] Add categorical features such as israin, issnow e t.c.
- [ ] Add neural neural network

# Team

- [Dmitrij Usachev](https//t.me/dmitrij_usachev)

# Sources

https://www.kaggle.com/datasets/muthuj7/weather-dataset/code
