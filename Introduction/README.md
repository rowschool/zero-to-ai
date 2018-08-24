# Zero to AI

## What is machine learning?

Machine learning is the combination of two things:
1. Statistics
2. Libraries

# need to go over what a library is ***

## What is intelligence?

Using data to modify behavior.

Input -> Black Box -> Output
Stimulus -> Black Box -> Response
Event -> Black Box -> Decision

The "black box" in this instance is data and your algorithm.
An intelligent algorithm improves in response to input data, prompting a sense of:
1. evolution
2. non-deterministic behavior

## What are types of intelligent algorithms?

- machine learning: capability of software to generalize phenomena (past or future) based on past experience
- artificial intelligence: software (and machines) that have a series of options to achieve a particular goal
- predictive analytics: capability of software to predict future outcomes based on historic data

## Types of Machine Learning

- Reinforcement learning (real-time decisions, robot navigation, learning tasks, skill acquisition, game AI)
- Supervised learning
  - Regression (advertising and popularity prediction, weather forecasting, market forecasting, estimating life expectancy, population growth prediction)
  - Classification (identity fraud detection, image classification, customer retention, diagnostics)
- Unsupervised learning
  - Clustering (recommender systems, targeted marketing, customer segmentation)
  - Dimensionality Reduction (big data visualization, meaningful compression, structure discovery, feature elicitation)

### Definitions/summaries

Regression - fitting data to predict where a new data point lies
Classification - applying labels to data
Clustering - finding groups within a population

## Supervised Learning

- Algorithms for which the potential outcomes are knowable in advance (i.e., category or numeric range) and can be used to correct the model's predictions

e.g.,
- Is a credit card holder a risk or not, given a set of features such as credit score, credit history, income, etc.?
- What is the estimated price of a house, given a set of features such as number of bedrooms, square feet, etc.?

## Regression

Predict the location of data points based on old data.

## Classification

Our focus is in identifying which pre-defined label our data falls into based on the features we have.

e.g.,
- Given a set of bananas and pears, what are the yellowness and asymmetry along these two axes, charted? Can we generalize these findings to future bananas and pears?
- Spam/Not Spam (ham)

## Unsupervised Learning

Algorithms for which the potential outcomes are unlabeled. Inferences are made directly from the data without feedback from known outcomes or labels.

## Clustering

We expect our algorithm to find the groupings of data points based on location.
These problems vary in complexity because sometimes the clusters may not be where we think they are. (e.g., from 3 expected clusters, our algorithm might only detect 2 obviously discrete clusters)

## Training and Predicting

Regardless of the type of problem, we will always follow a similar sequence of steps:
1. Model
2. Fit (Train)
3. Predict

Data goes into the model.
The model is trained based on the training data.
Then we test it to make sure that our expectations match what we've trained the model to do.
Then we'll tune our model's parameters to ensure that we get a desired outcome from our test data that matches with our training data.

Given a set of 1000 records, we'll use 80% for training and 20% for testing (like if we're predicting house prices and have all the data already).

We'll use test data to make new home price predictions with our model, compare what we predicted with the actual values from our data (Predicted vs. Actual), and we can get a score for our model based on how often we are correct. 

## With so many models to choose from, what do you choose?

*** Scikit-learn algorithm cheat-sheet

## Common Scoring Metrics

- R^2 (R-Squared): An R^2 value of 0.9 means that our model roughly accounts for 90% of the variability in the data, and is highly predictive.
- MSE (Mean Squared Error): measures the average of the squares of the errors or deviations
