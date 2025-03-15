# TODO

## To research and understand

- the different data types
- how to choose the correct test(comparison of groups.ipynb)
- understand the assumptions of linear regression
- What is predict proba?
- Exercises in classification 2, lots of questions about scalar
- Understand data drift
- shap, no categorial data?
- look at lambda
- look at transform (chapter 10 in book)
- what is predict_proba
- what does this do: [: , 0]?
- more
- research grid_search = GridSearchCV(estimator=rf, param_grid=param_grid, cv=5, scoring='accuracy', verbose=1)

- time series, the last 2 weeks are the last test, should not train on the whole time series, it's 5+ years, not neccessary

## To hand in
- completed
- 1 (Exercises in DT and EDA)
- 2 (DE_task)
- 3 (Exercises in statistics)
- 4 (Exercises in linear regression)
- 5 (TSA_Task)
- 6 (Exercises in classification)
- 7 (MQTT_Task)
- 8 (Exercises in clustering)
- 9 (mlflow & MLOps) DONT EVER RUN ME AGAIN
- 10 (Exercises in recommender systems)
- 11 (Exercises in neural network and deep learning 2)
- 12 (rag_task)
- 14 (Exercise in fairness in machine learning)
---
- to do
- 13 (run at home, again, explain)

# Homework

TSA_Task

- Bonus task?

Exercises In Classification 1

- needs refactoring,
- maybe add confusion matrixes to same plot

Exercises In Classification 2

- 1.8 (Optional)

pdm_task

- might need a review

MLOPS exercises

- might need a review
- also should have mlflow

mlflow_task

## Notes

- np convolve is really slow, use scipy.signal.fftconvolve instead

---

## Inference vs prediction

Inference: to understand and infer relation between input and output values, more advertising more sales?
Prediction: to be able to predict y given independent variables(x) with the least amount of error between actual and predicted values

If prediction is the goal you can go for higher flexible learning methods, like deep learning, though it might overfit
If inference is the goal a inflexible learning method could be desirable, like simple linear regression

## Parametric vs non-Parametric learning methods

Parametric learning methods: simple and tries to find the best learning model by changing parameters of a given function, like linear regression
doesn't need a lot of data

non-Parametric learning methods: tries different learning methods to find the best learning model, which is more expenisve to run and requires more data
to accurately make good predictions

In general
More flexable, more variance
More flexable less bias

## quotes

"When a given method yields a small training MSE but a large test MSE, we are
said to be overfitting the data." (An introduction to statistical learning, page 30)
