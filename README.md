# Classification-of-Mixed-Categorical-and-Numerical-data

This Python code illustrates how to do a classification on mixed data (categorical and numerical) with missed data using different ML models

the code is dealing with missed data from both numerical and categorical variables by different methods

categorical data should be converted into dummies variables first in order to do the classification

to overcome the unbalanced data, i did both oversampling and undersampling techniques 

unbalanced data could make the machine learning algorithm misclassify the variables

undersampling: in this technique, we Under-Sample the majority class(es) by randomly picking samples with or without replacement.

you have to make sure that after trying undersampling, you trying over-sampling also. so, you can compare between both methods

you can find the documentation of this python library here = https://imbalanced-learn.org/stable/references/generated/imblearn.under_sampling.RandomUnderSampler.html

for the oversampling i've used SMOTE (Synthetic Minority Oversampling Technique) which is a technique for imbalanced classification datasets.

SMOTE synthesizes new examples for the minority class.

SMOTE works by selecting examples that are close in the feature space, drawing a line between the examples in the feature space and drawing a new sample at a point along that line. Specifically, a random example from the minority class is first chosen. Then k of the nearest neighbors for that example are found (typically k=5). A randomly selected neighbor is chosen and a synthetic example is created at a randomly selected point between the two examples in feature space. (https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/)

