# Project Description

# Purpose: 
- A project that was just created for fun to explore one of the simplest but sometimes really efficient classifier, Naive Bayes Classifier. 

# Data Description:
- It is a very simple dataset commonly called as Tennis Dataset which contains weather conditions on a particular day and leaves it on the model to determine if it's a good day to play tennis or not. 

# Credits:
- Analytics Vidhya (https://www.analyticsvidhya.com/blog/2017/09/naive-bayes-explained/)
- scikitlearn documenation: https://scikit-learn.org/stable/modules/naive_bayes.html

# General Algorithm Description:
- One of the SIMPLEST CLASSIFICATION MODEL which is based on the Bayes Theorem (Conditional Probability).
- Usually works and preferred for quantitatively large datasets (MANY DATA POINTS or ROWS), with less features/predictors/columns. 
- Assumes that the features/predictors/columns are INDEPENDENTLY related to each other. 
- Example: Apple has features like - Shape, Size, and Color which are independent to each other.

# Math or Logic:
- The entire Math and Logic behind the working of this model can be found on the website on top of the page (with example).

# Pros or Advantages:
- Works for single-class and multi-class classification problems with similar logic. 
- Works quite fast with large datasets which has minimum or less number of features. 
- If the features are completely independent, it almost yields better results than logistic regression or other more complicated classfier. 
- Generally performs well with CATEGORICAL INPUT (one in the example above) than the numerical ones. For the numerical ones, a BELL CURVE is assumed (which is a strong assumption as it's hard to have one)

# Cons or Drawbacks:
- If an unknown CATEGORY is found in TEST DATA which wasn't present in TRAINING DATA, a probability of 0 is assigned which might interfere with the results. To solve this,a smoothing technique called "Laplace Estimation". Please note that we cannot take a ZERO PROBABILITY for any category because ZERO CATEGORY would mean that it's IMPOSSIBLE for such a data to exist. That's a CONTRADICTION because the data is existing in test set. Also, logically and ethically, if a category cannot be found in training set, it doesn't mean that it cannot be found at all in real-world. That's why we need to use SMOOTHING TECHNIQUES!
- It's almost impossible to find data whose predictors are INDEPENDENT. So assuming the independence among the features is rather a hard assumption. 

# Applications:
- Can be found on credits website link!
