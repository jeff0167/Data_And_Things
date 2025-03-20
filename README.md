# TODO

## To research and understand

- the different data types
- how to choose the correct test(comparison of groups.ipynb)
- understand the assumptions of linear regression
- What is predict proba?
- Exercises in classification 2, lots of questions about scalar
- Understand data drift
- look at lambda?
- look at transform (chapter 10 in book)
- what is predict_proba?
- what does this do: [: , 0]? all from first dimension, on second dimension select first row/column
- loss function
- cost function
- apply v transform
- look at fairnes in machine learning again
- check assumptions problems of linear regression(Original)
- ALLOWED ALL HJÆLPE MIDLER, CAN ADD STUFF TO THE CODE
- more
- research grid_search = GridSearchCV(estimator=rf, param_grid=param_grid, cv=5, scoring='accuracy', verbose=1)

###### tp fn   tp + fn  precision, how many we get predict right ratio        tp + fp   sensitivity        accuracy, how many we hit(predict) correctly tp & tn, hit the target
###### fp tn   fp + tn  recall,    how many we predict false ratio            fp + tn   speicificity       f1, a score for all of it, kinda


the difference between data sets is called variance
so when seing difference between training and test it's variance

bias is on the training set, the inability to capture the true relationship
low bias fits fell(prop overfit), high bias(underfit) fits bad on the data, like a line that tries to capture a curve

Data lake:
    A vast, centralized repository that allows you to store all your structured, semi-structured, and unstructured data at any scale.
    Stores raw, unprocessed data from various sources.
    It stores data in its native format.

Data warehouse:
    A repository of structured, filtered, and transformed data, specifically designed for querying and analysis.
    It focuses on storing data that has been processed for specific business purposes.

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
- 13 (explain)
- 14 (Exercise in fairness in machine learning)

## Notes

- np convolve is really slow, use scipy.signal.fftconvolve instead
- recommender systems
- simple, ranked/popular movies
- content, similar movies base on one movie
- collaborative, movies other similar users have watched

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


## hacks
- zoom in, set x interval to look at
- plt.xlim(0, 60)  # Set the x-axis limits
- plt.xticks(range(0, 61, 10))  # Set x-ticks every 10 units
