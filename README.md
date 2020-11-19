# machine-learning-challenge
Classifying candidate exoplanets from the raw dataset using the following Machine Learning models:
- Logistic Regression
- Deep Neural Network
- Support Vector Machine (SVM) with Grid Search

**Comparing the 3 Models** 

In prediction the new exoplanets, the testing data set scores 84.3% when using Logistic regression model, 87.8% when using Deep neural network model, 84.1% when using Support Vector Machine, and 87.1% when usiong SVM with `GridSearch` to tune the model's parameters. The slightly higher scores from Deep neural network and SVM with `GridSearch` are due to the more computing power that these two models were supplied with.  

Given the model's score, Logistic and SVM models may be good enough to predict new exoplanets. Deep neural network and SVM with hyper paramaters tuning could probably be improved to give even more accurate scores in making the predictions by addition of computing power. This can be done by supplying more hidden layers to the Deep neural network model and supplying more hyperparameters to  and SVM's `Gridsearch` model. 