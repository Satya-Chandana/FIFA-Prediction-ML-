# FIFA-Prediction-ML-

## Introduction:

FIFA is also a series of video games developed by EA Sports which faithfully reproduces the characteristics of real players. Data from this website for 2019 were scrapped and made available at the Kaggle webpage https://www.kaggle.com/karangadiya/fifa19.

The original dataset contains 89 variables that describe 16,924 players. The variables include information such as age, nationality, club, wage, etc.


We predict two dependent variables: <br />
#### 1.Market Value: 
The market value of a player can determine the amount of money that clubs can demand for a transfer. Factors like personal form, importance to the team, stats, contract length and age can strongly influence the market value of a player. 
#### 2.Position:  
It is the position in which the player plays, such as attack, middle, defense, or goalkeeper. <br />
<br /> <br />
Regression:
We predicted the market value of players by regression. The models used are: <br />
1.Simple Linear Regression <br />
2.Multiple Linear Regression <br />
3.KNN <br />

Classification:
We predicted the Position of players using classification. We use several models like Decision tree, Random Forest, etc.

## Algorithms used:

### Supervised learning algorithms:
SVM <br />
KNN <br />
Decision Tree <br />
Random forest <br />
Naive bayes <br />

### Unsupervised learning algorithms:
K-Means Clustering <br />
Birch clustering <br />
Agglomerative clustering <br />

### Boosting algorithms:
XGboost <br />
Light gradient boosting Machine (LGBM)
 
 
## Result analysis:

Accuracy of Decision Tree: 0.8212075954768508 <br />
Accuracy of LGBM: 0.8756133987625346 <br />
Accuracy of XGBoost: 0.8653723063793471 <br />
Accuracy of SVM: 0.7559206315340303 <br />
Accuracy of Random Forest: 0.8724130573927885 <br /> 
Accuracy of Naive Bayes: 0.7277576274802645 <br />
Accuracy of KNN: 0.8156603371026243 <br />
Accuracy of K-Means: 0.3891615105611265 <br />
Accuracy of Agglomerative Clustering: 0.2613612118625987 <br /> 
Accuracy of Birch Clustering: 0.2613612118625987 <br />

Bar graph for the Accuracy Scores of all the models:
![image](https://user-images.githubusercontent.com/75208415/212074212-05dc66cb-8125-462e-970d-04bd35b67616.png)

Bar graph for the F1 Scores of all the models
![image](https://user-images.githubusercontent.com/75208415/212075175-8c776fe7-ba3f-4e10-a53d-fd9c90e7fec9.png)

Scatter plot for the Accuracy and F1 scores
![image](https://user-images.githubusercontent.com/75208415/212074276-d6f84a28-1eb4-43d8-9915-0b7ecda6cbd8.png)
 

From the above plots and the scores, we can see that LGBM (Light Gradient Boosting Machine) model gave the highest F1 score which means it is the perfect model for predicting.
Two other models which can be used for this data set are Random Forest Classifier and XG Boost as they give a better accuracy after the LGBM model.

#### Copy of Code: 
Please refer this for the colab notebook -
https://colab.research.google.com/drive/1AC96v36bfog2V8A9gAm6BgUSLmDgX-aZ?usp=sharing




