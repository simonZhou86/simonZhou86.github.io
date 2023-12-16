---
title: "Predicting cuisine category using recipe ingredients"
excerpt: "Use recipe ingredients to categorize the cuisine through machine learning and deep learning models.<br/><img src='/images/whats_cooking.png'>"
collection: portfolio
---

**Project Intro:**
In this project, we leveraged various traditional machine learning and deep learning methods to predict the category of a dish’s cuisine given a list of ingredients that used in the dish.

**Data description:**
Training dataset is in JSON format and has three attributes: recipe ID (int), the type of cuisine(object/string), and the list of ingredients (object list). Test dataset only have two attributes: recipe ID and the list of ingredients. Both attributes have the same format as they appear in Training dataset.

**Data Preparation & Feature Engineering:**
- Since the format of both training and testing dataset is the combination of string and numeric, we have to somehow convert string into numeric value for modelling.
- Removing the special characters, numbers and units(if any) in each ingredient, those may affect the true value when converting to numeric.
- Standardized words (convert all letters to lower case, remove hyphen, change word to default tense)
- Using TF-IDF algorithm to extract some significant(unique) ingredients for each recipe and convert to numeric value, this will be the features for that recipe. The result matrix is a sparse matrix.
- Since the matrix after TF-IDF is a spare matrix with a large dimension, we consider SVD method to reduce the dimension. In this case, we perform truncated SVD algorithms.

**Modelling:**
- Logistic Regression with OVR
- Support Vector Machine with OVR and linear boundary (using linear boundary due to hardware limitation)
- Random Forest
- Boosting and voting classifier
- Neural Networks
- Hyper-parameter tuning is done via GridSearchCV in Python. Random Forest and boosting & voting classifier is not reported due to low accuracy on validation dataset.

The code for this project can be found at [this url](https://github.com/simonZhou86/Kaggle-Competition)
Original Kaggle Competition [link](https://www.kaggle.com/c/whats-cooking-kernels-only/overview)


If you want to use the code, or find our project useful, you can set as follows:

```{bibtex}
@misc{mz2020whats,
    author = {Zhou, Meng},
    title = {What's Cooking: Predicting cuisine category using recipe ingredients},
    year = {2020},
    howpublished = {\url{https://simonzhou86.github.io/portfolio/whats_cooking}},
}
```