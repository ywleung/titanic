This project contains IPyhton Notebook files for a Kaggle competition <a href="https://www.kaggle.com/c/titanic">Titanic: Machine Learning from Disaster</a>.
The results should score around 0.8, top 5% of the leaderboard.

titanic EDA.ipynb performs Exploratory Data Analysis on the train set.
titanic model.ipynb performs feature engineering and modeling(Linear Regression, SVM, Random Forrest and other model in sklearn)

Conclusion:
1) gender, title, fare are the most important features to the prediction
2) ensemble model outperforms any single model
3) tree-based models are easily overfitting
4) simple model performs better than MLP

Further work:
1) use xgboost/ lightgbm (always get a good result in Kaggle competition)
2) find out other magic features
