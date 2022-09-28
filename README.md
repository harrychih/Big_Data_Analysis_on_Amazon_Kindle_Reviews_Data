# Big Data Analysis on Amazon Kindle Reviews Data

## Introduction

This is a course project concerning about predicting amazon kindle books rating that was done in the big data analytics (Winter 2021) course at University of California, Santa Barbara. 

## Author

Yanjie Qi, Nathan Ng, Peter Ayral, Kaden Nguyen

## Abstract

In this project, we utilized Kindle reviews from Amazon in order to predict the sentiment of the review for the product. We incorporated 9 different features into our models: overall, review_features, summary_features, weightedRating, HasHelpful, asin_vector, reviewTime_vector. We modified the overall column to show 1 if the overall score was greater than or equal to 3 (positive review) and 0 if the overall score was less than or equal to 2 (negative review). In order to clean and preprocess the data we used Tokenizer to make words into arrays and StopWordsRemover to remove basic words. To help accurately predict the sentiment of the reviews we employed models of Linear Regression (benchmark model), Logistic Regression, Naive Bayes, and Random Forest. By evaluating each model based on its test accuracy, test recall, test precision, and F1 score we were able to find our champion model of Naive Bayes as it possessed the great results in terms of its test accuracy, test precision, and F1 score as well as its highly interpretable nature. However, all of our models were pretty accurate as our champion model was narrowed down under the criteria of processing time and interpretability.

## Research Question

- What Statistical Methods Best Predict the Overall Rating of Amazon Kindle Reviews?

## Reference

- https://christophm.github.io/interpretable-ml-book/other-interpretable.html
