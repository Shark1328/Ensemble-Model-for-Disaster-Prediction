# Ensemble-Model-for-Disaster-Prediction
An ensemble classification model for predicting survivors of the Titanic wreck.

The details about the code are as follows:

1. In the part of data analysis, focus on observing the statistical factors of independent variables, such as linearity, kurtosis, and normality, through pandas and seaborn, and observe the image relationship between each variable and the target variable.
2. In the feature engineering part, in order to avoid over-fitting and exclude some extreme values, the default value is filled with the median value, average value, effective value distribution, etc. through the digital nature of the independent variable.
3. In the modeling part, 10 models including Decision Book, AdaBoost, Random Forest, GradientBoost, and K-Neighbor Classifier were used for cross-entropy verification and scoring. Select five models of Random Forest, ExtraTree, SVC, AdaBoost and GradientBoost, and set the detailed parameters. Finally, five models are integrated through sklearn's VotingClassifier model to form the final voting classifier.

The dataset of this project comes from Kaggle, mainly about the information of each passenger on the Titanic, including quantified family situation, seat information, etc.

The link is here, https://www.kaggle.com/competitions/titanic
