# Predictive-Maintainance-Multitasklearning
This is to create a model for predicting RUL(Remaining Useful Lifetime) and FP(Failure prediction), using a single neural network using multitask learning.

Here I have used NASA's dataset for engine lifetime.

Here the goal is to compare the single task learning models with multi task learning models.
The first model is to predict RUL(Remaining Useful Lifetime) of the engine. This model predicts the value as a regression problem. 
  The model building and evaluation is shown [Here](https://github.com/sachinmathewjose/Predictive-Maintainance-Multitasklearning/blob/master/Predicting_RUL.ipynb)
The second model is to predict the failure (FP- Failure Prediction). This model predicts the value as a classification problem. 
  The model building and evaluation is shown [Here](https://github.com/sachinmathewjose/Predictive-Maintainance-Multitasklearning/blob/master/Predicting_FP.ipynb)
The third model is to predict both RUL and FP using a multi-task learning model.
   The model building and evaluation is shown [Here](https://github.com/sachinmathewjose/Predictive-Maintainance-Multitasklearning/blob/master/predictive_maintenance_multitaskLearning.ipynb)
   
All the project is done using Keras in tensor-flow back-end using Google colab.
#### TO DO
  - [ ] \(Optional) Use weibull distribution instead of predicting RUL directly. This helps in predicting the useful life time with a limited amount of data. This is the case in many real world dataset, because the failure events are rare in real-life.
