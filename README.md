# ensemble-learning-football-predictor


<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/pawelp0499/ensemble-learning-football-predictor?style=plastic"> <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/pawelp0499/ensemble-learning-football-predictor?style=plastic">




## Project's purpose
**Why? What's new?**

☑️ Classic models often turn out to be inefficient in the specifics of football prediction, especially in predicting draw results

☑️ In this area, there is a lot of space for further search for increasingly optimal solutions


**Main goals**

🎯 Test Ensemble learning technique in the specificity of football prediction

🎯 Combine several individual models to produce more accurate predictions than a single model alone

🎯 Compare efficiency of ensemble predictors vs individual ones

🎯 Searching for the optimal predictor and build it as strong as possible




## Description

The project presents several machine learning approaches to predicting football match results. The focus is on the games of 4 major football leagues - English, Spanish, German and Italian, from a period of about 10 seasons. The main point of the research was the construction of ensemble learning algorithms (voting, boosting, bagging), but classic single models of multi-class prediction and binary classification were also presented. Mainly for the purpose of comparing the obtained results and trying to better understand and explain of the complexity of predicting football events.

🔥 4 top leagues

🔥 more than 18 000 matches from 13 seasons (2010/11 - 2022/23)

🔥 more than 20 separate machine learning algorithms


## Content



**Individual algorithms:**

◾ Decision Tree (DT)

◾ Multinomial logistic regression (MLG)

◾ Multi-layer Perceptron (MLP)

◾ k-Nearest Neighbors (KNN)

◾ Gaussian Naive Bayes (GNB)

**Ensemble algorithms:**

◾ Random forest - as example of the bagging method

◾ XGBoost - as example of the boosting method

◾ Majority Voting Algortihms

◾ Weighted Voting Algortihms

**Binary classificator:**

◾ Random forest


✅ For each of the above algorithms, the GridSearch method was used to search for a set of optimal hyperparameters.



## Built with

**Tech:** Python language with the following libraries

🔧 Pandas 🔧 Numpy 🔧 GridSearchCV 🔧 Scikit-learn 🔧 Seaborn 🔧 Xgboost 🔧 Plotnine 🔧 Matplotlib   



## Run

Clone repository

```
$ git clone https://github.com/pawelp0499/ensemble-learning-football-predictor.git
```

Choose correct directory

```
$ cd ensemble-learning-football-predictor
```

All content in .ipynb file

```
main.ipynb
```

## Icons



Copyright (c) 2024 Paweł Pechta