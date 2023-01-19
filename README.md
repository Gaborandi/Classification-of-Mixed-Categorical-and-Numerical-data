# Classification-of-Mixed-Categorical-and-Numerical-data
This Python code illustrates how to do a classification on mixed data (categorical and numerical) using different ML models

the code is dealing with missed data from both numerical and categorical variables

categorical data should be converted into dummies variables first

to overcome the unbalanced data, i did both oversampling and undersampling techniques 

undersampling: in this technique, we Under-Sample the majority class(es) by randomly picking samples with or without replacement.

you have to make sure that after trying undersampling, you trying over-sampling also. so, you can compare between both methods

you can find the documentation of this python library here = https://imbalanced-learn.org/stable/references/generated/imblearn.under_sampling.RandomUnderSampler.html
