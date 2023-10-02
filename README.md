# Liver-Disease-Prediction-Research
## This repo contains:</br>
1. Kaggle code on my undergrad thesis
2. The pdf file for the corresponding thesis book
3. The pdf file of the paper titled "LIVER DISEASE PREDICTION USING ENSEMBLE STACKING APPROACH INTEGRATING ADVANCED MACHINE LEARNING MODELS", which is a paper I'm currently working on and which is submitted to "26th International Conference on Computer and Information Technology".
## How to run the codes?
1. The entire proect was built in Kaggle. So, at first after logging in to the Kaggle, a new notebook has to be created. Now, after creating the notebook, from file options the 'import notebook' option has to be selected and the corresponding notebook has to be uploaded.
2. Then "Indian Liver Patient Records" dataset has to be added.<br>
Now the code should run just fine.
## Why do I have 12 separate codes and how did I name them? 
In my research, I tried to find the best possible combination of Data Processing techniques and the Classification Algorithms. This is why I iteratively combined different Data Processing methods with nine different classifiers, which are: XGBoost, Random Forest, CART, Ensemble Stacking, Logistic Regression, KNN, ANN, SVB & Gaussian Naive Bayes.</br>
For all the iterations, I kept the same methos for missing value imputation which happens to be MICE.</br>
For all the iterations, I kept the same normalization technique, which happens to be standardization by using __StandardScaler__ from __scikit-learn__.</br>
In case of Data Balancing and Feature Reduction techniques I tried different combinations of techniques. </br></br>

### 1st iteration "data-normalypsample-final.ipynb"
It means the data balancing method used iss simple minority upsamling by using the __resample__ fuction from __scikit-learn__ like library. And no feature reduction technique waa used.

### 9th iterarion "rose-pca-final.ipynb"
It means the data balancing method used is ROSE. And the feature reduction technique used is PCA. 

This is how all the codes have been named based on th work done on that iteration.
## What are the pdf files?
1. "Thesis_1710022" contains the preliminary report of my undergrad thesis in the form of a book.
2. "Paper_1710022" contains the paper on which I'm workng on and which has been submitted at 26th ICCIT.


